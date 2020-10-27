import csv
def writing_into_csv(list):
     with open('student_info.csv','a',newline='')as csv_file:
        writer=csv.writer(csv_file)
        if csv_file.tell()==0:
             writer.writerow(["Name","Age","Contact.no","Email id"])
        writer.writerow(list)


if __name__=='__main__':
   condition=True
   student=1
   print("Enter the information of the student-")
   while(condition):
    w=input("Enter the name:")
    x=input("Enetr the age:")
    y=input("Enter the  contact:")
    z=input("Enter the email id of student:")
    student_info=[w,x,y,z]
    print("\nEntered information for student {}:\n".format(student))
    print("Name:{}".format(w))
    print("Age:{}".format(x))
    print("Contact number: {}".format(y))
    print("Email id : {}".format(z))
    Check_info=input("\nif information is correct enter(yes) else enter (no)")
    student=student+1
    if Check_info=="yes":
        writing_into_csv(student_info)

        Next = input("\nEnter (yes) for entering next students information elese enter (no):")
        if Next == "yes":
            condition = True
        elif Next == "no":
            condition = False

    elif Check_info=="no":
        print("\nre-enter correct information")

