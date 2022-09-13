# BMI-calculator
Bmi = float(weight / (height)**2)

if Bmi < 18.5 :
  print(f"Your Bmi is {round(Bmi)}, you have a underweight. ")
elif 18.5 <= Bmi <= 25 :
  print(f"Your Bmi is {round(Bmi)}, you have a normal weight" )
elif 25 < Bmi <= 30 :
  print(f"Your Bmi is {round(Bmi)}, you are slightly over weight" )
elif 30 < Bmi <= 35 :
  print(f"Your Bmi is {round(Bmi)}, you have an obese" )
else:
  print(f"Your Bmi is {round(Bmi)}, you have a clinicaly obese" )
