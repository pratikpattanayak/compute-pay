# compute-pay
This small code is used to compute salary of an employee.



def computepay(hours,rate):
 if hours>40.0:
  p = rate * 40.0
  p = p+(1.5*rate*(hours-40))
 else:
  p = rate*hours
 return p
hours = float(input("Enter worked hours: "))
rate = float(input("Enter Pay rate per hour: "))
print (computepay(hours,rate))
