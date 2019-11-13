# labspy03
* latihan1.py,

n = int(input("Masukkan nilai N:"))

from random import random

a = random()

jumlah = n

for i in range(jumlah):

   print("data ke:", i,(a))
    
print("selesai")

![image](https://user-images.githubusercontent.com/56722786/68598414-9a8dc380-0453-11ea-9ba3-51dae587ed02.png)


* latihan2.py,

print("Program menampilkan bilangan terbesar dari n bilangan")

a = 1

max = 0

while a !=0:

  if a > max:
    
   max = a
   
   a = int(input("Masukkan bilangan:"))
    
   if a == 0:
    
   break
        
print("Nilai terbesar adalah:", max)

![image](https://user-images.githubusercontent.com/56722786/68598885-77afdf00-0454-11ea-9c30-91963b43e041.png)


* program1.py

x=1000000000

sum=0

y=0

laba = [int(0), int(0), int(x) * .1, int (x) * .1, int(x) * .5, int(x) * .5, int(x) * .5, int(x) * .2]

print("Modal awal seorang pengusah:", x)

for i in laba :
    sum = sum+i
    
   y+=1
    
   print("Laba bulan ke-",y,"sebesar:", i)
    
print("Total laba adalah;",sum)

![image](https://user-images.githubusercontent.com/56722786/68599872-46381300-0456-11ea-8c03-4868669d1718.png)
