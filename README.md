#create class and object easily
class Person:
    def SetValues(self,name,age):
        self.name=name
        self.age=age
    def GetValues(self):
        print("The person name is:",name,"and his age is:",age)
#create object for class
p=Person()
name=input("Enter ur name:")
age=int(input("Enter ur age"))
p.SetValues(name,age)
p.GetValues()
