a=input("Введите строку: ")
b=0
c=0
for i in a:
    if i.isalpha():
        b+=1
    elif i.isdigit():
        c+=1
print('Количество букв: ',b)
print('Количество цифр: ',c)