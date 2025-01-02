class Student:
    def _init_(self, name, roll_no, address, college, department, year):
        self.name = name
        self.roll_no = roll_no
        self.address = address
        self.college = college
        self.department = department
        self.year = year

    def display_details(self):
        print("\nStudent Details:")
        print(f"Name: {self.name}")
        print(f"Roll No: {self.roll_no}")
        print(f"Address: {self.address}")
        print(f"College: {self.college}")
        print(f"Department: {self.department}")
        print(f"Year: {self.year}")

# Using your details
student = Student(
    name="Shakunthala R",
    roll_no="53",
    address="Deetur",
    college="GPTH",
    department="CS",
    year="6th Sem"
)

# Displaying your details
student.display_details()
