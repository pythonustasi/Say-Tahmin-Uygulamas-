# Say-Tahmin-Uygulamas-
Makina'nın tuttuğu sayıyı bilebilir misin?
# Say-Tahmin-Uygulamas-
#Makina'nın tuttuğu sayıyı bilebilir misin?
import random
secim = input("Zorluk Seviyesi(1, 2, 3) : ")
if(secim == 1):
  tutulanSayi = random.randint(0,10)
  soylenensayi = -1
  sayac = 0
  while sayac<=3:
    if(sayac == 3):
      print("yarışmayı kaybettiniz.")
      break
    sayac += 1
    soylenensayi = input("Bir sayı söyleyin(0 - 10 arası): ")
    if(soylenensayi == tutulanSayi):
      print("Yarışmayı Kazandınız.")
      break
    print("Tekrar Deneyin!")
      
elif(secim == 2):
  tutulanSayi = random.randint(0,20)
  soylenensayi = -1
  sayac = 0
  while sayac<=4:
    if(sayac == 4):
      print("yarışmayı kaybettiniz.")
      break
    sayac += 1
    soylenensayi = input("Bir sayı söyleyin( 0 - 20 arası): ")
    if(soylenensayi == tutulanSayi):
      print("Yarışmayı Kazandınız.")
      break
    print("Tekrar Deneyin!")  
elif(secim == 3):
  tutulanSayi = random.randint(0,100)
  soylenensayi = -1
  sayac = 0
  while sayac<=5:
    if(sayac == 5):
      print("yarışmayı kaybettiniz.")
      break
    print("Tekrar Deneyin!")
    sayac += 1
    soylenensayi = input("Bir sayı söyleyin(0 - 100 arası): ")
    if(soylenensayi == tutulanSayi):
      print("Yarışmayı Kazandınız.")
      break
else:
  print("Lütfen geçerli bir seviye girin...")
