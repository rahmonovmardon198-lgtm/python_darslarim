
#print('nima qivosan harakat va yana harakat qil')
#print(5**2)
#print(22%4)
#a=125
#print('kvadrat yuzi S=a**2=',125**2)
#print('kvadrat premetri P=4*a=',4*125)
#d=12
#P=3.14
#print('doiraning yuzi S=P*d^2/4',(P*d**2)/4)
#a1=6
#a2=7
#print("to'g'ri burchakli uchburchak gipotenuzasi",(a1**2+a2**2)**1/2)

# ism=input('ismingiz nima?\n')
# print('assalomu aleykum,'+ism.title())

# son=float(input('son kiriting>>>'))
# a=son**2
# b=son**3
# print('siz kiritgan son kvadrati va kubi',a,'va',b, 'larga teng ')

# yosh=int(input('yoshingiz nechida?'))
# t_yil=2025-yosh
# print(f'siz {t_yil} yilda tug\'ilgansiz')

# a=float(input('a sonni kiriting; a='))
# b=float(input('b sonni kiriting; b='))
# print(f'''a+b={a+b} 
# a-b={a-b}
# a*b={a*b}
# a/b={a/b}''')

# ismlar=['Sanjar','Jahongir','Nodir']
# print('salom ',ismlar[0],'bugun choyxona bormi?',ismlar[1],'choyxonaga boramizmi?',ismlar[2],'qatttasiz')

# sonlar=[10,-5,1.2,13.4,-7.5]
# print(sonlar)
# print(sonlar[0]+sonlar[4])
# sonlar[0]=sonlar[0]+2.3
# print(sonlar[0])

# sonlar.sort()
# print(sonlar)

# print(sorted(sonlar))
# print(sorted(sonlar,reverse=True))

# juft_sonlar = list(range(0,20,2)) # 0 dan 20 gacha 2 qadam bilan
# toq_sonlar = list(range(1,20,2))  # 1 dan 20 gacha 2 qadam bilan
# print("Juft sonlar: ", juft_sonlar)
# print("Toq sonlar: ", toq_sonlar)

# narhlar = [12000, 22500, 23456, 9800, 5600, 9934, 32874]
# arzon = min(narhlar)
# qimmat = max(narhlar)
# jami = sum(narhlar)
# print("Eng arzon narh ", arzon, ". Eng qimmati ", qimmat, ". Jami: ", jami)




# # 8-dars (listlar bilan ishlash)

# viloyatlar=['Toshkent','Samarqand','Buxoro','Andijon','Namangan']
# print(viloyatlar)
# print(len(viloyatlar))
# print(sorted(viloyatlar))
# print(sorted(viloyatlar,reverse=True))
# sonlar=list(range(120,1201,2))
# print(sonlar)
# jami=sum(sonlar)
# print(jami)
# print(sum(sonlar))
# print(max(sonlar)-min(sonlar),'= max-min ')
# print(len(sonlar),'ta son mavjud')
# print(sonlar[:21])
# print(sonlar[270:291])
# print(sonlar[520:])

# taomlar=['mastava','kabob','osh','xonim','chuchvara']
# nonushta=taomlar[:]
# nonushta.remove('mastava')
# nonushta.remove('chuchvara')
# nonushta.append('amled')
# nonushta.append('moy non')
# print('taomlar',taomlar,)
# print('nanushta',nonushta)
# nonushta=tuple(nonushta)
# # nonushta[0]='qaymoq va non'



# 9-dars (For)

# ismlar=['Sanjar','Mardon','Nodir','Said','Akmal']
# for ism in ismlar:
#     print(f'salom {ism}')
# print('kod',len(ismlar),'marta takrorlandi')

# sonlar=list(range(11,100,2))
# for son in sonlar:
#     print(son**3)
# print('10 dan 100 gacha toq sonlar kubi')

# kinolar=[]
# for n in range(5):
#     kinolar.append(input(f'{n+1}-kinoni kiriting:'))
# print(kinolar)

# suhbatlar_soni=int(input('bugun nechta odam bilan suhbatlashdiz:'))
# odamlar=[]
# for n in range(suhbatlar_soni):
#     odamlar.append(input(f'{n+1}-odamni ismi:'))
# print(odamlar)



# 10-dars (if-else)

# cars = ['toyota', 'mazda', 'hyundai', 'gm', 'kia']
# for car in cars:
#     if car.lower()=='gm':
#         print(car.upper())
#     else:
#         print(car.title())

# cars = ['toyota', 'mazda', 'hyundai', 'gm', 'kia']
# for car in cars:
#     if car.lower()!='gm':
#         print(car.title())
#     else:
#         print(car.upper())

# foydalanuvchi=input('login kiriting:')
# if foydalanuvchi.lower()=='admin':
#     print('Xush kelibsiz,',foydalanuvchi.title(),"Foydalanuvchilar ro'yxatini ko'rasizmi?")
# else:
#     print('Xush kelibsiz,',foydalanuvchi.title())

# a=int(input('birinchi sonni kiriting:'))
# b=int(input('ikkinchi sonni kiriting:'))
# print('ikki son bir biriga teng') if a==b else print('ikki son bir biriga teng emas')

# son=float(input('son kiriting:'))
# if son>0:
#     print('kiritilgan son musbat')
# elif son<0:
#     print('kiritilgan son manfiy')    
# else:
#     print('kiritilgan son 0 nomanfiy nomusbat')    

# son=float(input('musbat son kiriting:'))
# if son>=0:
#     print('kiritilgan son kvadrat ildizi',son**(1/2),'ga teng')
# else:
#     print('kiritilgan son musbat emas')



# 11-dars (bir nechta shartlar bilan ishlash)











