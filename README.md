str=input(('Enter a String'))

x=str.split()
ls = []  
for i in x:

    y = x.count(i)  
    ls.append((i,y))       


dict1 = dict(ls)

print (dict1)
print('hii')
