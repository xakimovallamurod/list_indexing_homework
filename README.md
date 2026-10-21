# Ro'yxat indekslari

## List01

Bo'sh ro'yxat qaytaring.

**Misol 1:**

```Python
Kirish: 
Chiqarish: []
```

---

## List02

Allamurod o'rganayotgan fanlar ro'yxati berilgan. Birinchi fanni qaytaring.

**Misol 1:**

```Python
Kirish: fanlar=["Python", "Matematika", "Ingliz tili"]
Chiqarish: "Python"
```

---

## List03

Allamurodning ikki javondagi kitoblari ro'yxati list1 va list2 berilgan. Ularni birlashtirib qaytaring.

**Misol 1:**

```Python
Kirish: list1=["Python asoslari", "Algoritmlar"], list2=["Toza kod"]
Chiqarish: ["Python asoslari", "Algoritmlar", "Toza kod"]
```

---

## List04

Allamurodning oylik daromadlari ro'yxati berilgan. Oxirgi oy daromadini qaytaring.

**Misol 1:**

```Python
Kirish: royxat=[6500000, 7200000, 6800000]
Chiqarish: 6800000
```

---

## List05

Ro'yxat va indeks i berilgan. i-indeksdagi elementni qaytaring.

**Misol 1:**

```Python
Kirish: royxat=["Allamurod", "Xakimov", 26, "Toshkent"], i=2
Chiqarish: 26
```

**Misol 2:**

```Python
Kirish: royxat=["Allamurod", "Xakimov", 26, "Toshkent"], i=-1
Chiqarish: "Toshkent"
```

---

## List06

Allamurodning 5 kunlik sport jadvali berilgan: 1 — sport zaliga bordi, 0 — bormadi. Ro'yxatdagi barcha `1` larni `True` ga almashtirib qaytaring (indekslar orqali).

**Misol 1:**

```Python
Kirish: royxat=[1, 0, 1, 1, 0]
Chiqarish: [True, 0, True, True, 0]
```

---

## List07

Allamurodning 5 kunlik sport jadvali berilgan: 1 — sport zaliga bordi, 0 — bormadi. Ro'yxatdagi barcha `0` larni `False` ga almashtirib qaytaring (indekslar orqali).

**Misol 1:**

```Python
Kirish: royxat=[1, 0, 1, 1, 0]
Chiqarish: [1, False, 1, 1, False]
```

---

## List08

Allamurodning 5 kunlik sport jadvali berilgan: 1 — sport zaliga bordi, 0 — bormadi. `1` larni `True` ga, `0` larni `False` ga almashtirib qaytaring.

**Misol 1:**

```Python
Kirish: royxat=[1, 0, 1, 1, 0]
Chiqarish: [True, False, True, True, False]
```

---

## List09

Uch elementli ro'yxat berilgan. Agar barcha elementlar bir xil bo'lsa `True`, aks holda `False` qaytaring.

**Misol 1:**

```Python
Kirish: royxat=[26, 26, 26]
Chiqarish: True
```

**Misol 2:**

```Python
Kirish: royxat=[26, 29, 26]
Chiqarish: False
```

---

## List10

Sonlar ro'yxati berilgan. Birinchi va oxirgi elementdan kattasini qaytaring.

**Misol 1:**

```Python
Kirish: royxat=[6500000, 7200000, 6800000]
Chiqarish: 6800000
```

**Misol 2:**

```Python
Kirish: royxat=[9, 1, 5]
Chiqarish: 9
```

---

## List11

Toq sondagi elementlardan iborat ro'yxat berilgan. O'rtadagi elementni `len()` yordamida topib qaytaring.

**Misol 1:**

```Python
Kirish: royxat=["Dushanba", "Seshanba", "Chorshanba", "Payshanba", "Juma"]
Chiqarish: "Chorshanba"
```

**Misol 2:**

```Python
Kirish: royxat=[87, 92, 78]
Chiqarish: 92
```

---

## List12

Ro'yxat berilgan. Birinchi va oxirgi elementlarning o'rnini almashtirib, ro'yxatni qaytaring.

**Misol 1:**

```Python
Kirish: royxat=["Allamurod", "Python", "Xakimov"]
Chiqarish: ["Xakimov", "Python", "Allamurod"]
```

**Misol 2:**

```Python
Kirish: royxat=[1, 2, 3, 4]
Chiqarish: [4, 2, 3, 1]
```

---

## List13

Allamurod haqidagi ma'lumotlar ro'yxati berilgan: [ism, familiya, tug'ilgan yil, shahar]. Yoshni 2026-yil bo'yicha hisoblang va "<ism> <familiya>, <yosh> yosh, <shahar>" satrini qaytaring.

**Misol 1:**

```Python
Kirish: malumot=["Allamurod", "Xakimov", 2000, "Toshkent"]
Chiqarish: "Allamurod Xakimov, 26 yosh, Toshkent"
```

---

## List14

Allamurodning uchta fandan olgan ballari ro'yxati berilgan. O'rtacha balni hisoblang va 1 xona aniqlikda yaxlitlab qaytaring.

**Misol 1:**

```Python
Kirish: ballar=[87, 92, 78]
Chiqarish: 85.7
```

**Misol 2:**

```Python
Kirish: ballar=[90, 90, 90]
Chiqarish: 90.0
```

---

## List15

Allamurodning to'rt oylik daromadlari ro'yxati berilgan. Ikkinchi element va oxiridan ikkinchi element yig'indisini qaytaring.

**Misol 1:**

```Python
Kirish: royxat=[6500000, 7200000, 6800000, 7000000]
Chiqarish: 14000000
```

---

## List16

Sana [kun, oy, yil] ro'yxati ko'rinishida berilgan. Funksiya ichida oy nomlari ro'yxatini yarating ("yanvar", ..., "dekabr") va "<kun>-<oy nomi> <yil>-yil" satrini qaytaring.

**Misol 1:**

```Python
Kirish: sana=[15, 3, 2000]
Chiqarish: "15-mart 2000-yil"
```

**Misol 2:**

```Python
Kirish: sana=[1, 9, 2026]
Chiqarish: "1-sentyabr 2026-yil"
```

---

## List17

Ro'yxat, indeks i va yangi qiymat berilgan. i-indeksdagi elementni yangi qiymatga almashtirib, ro'yxatni qaytaring. Agar indeks chegaradan chiqsa, ro'yxatni o'zgarishsiz qaytaring.

**Misol 1:**

```Python
Kirish: royxat=["Allamurod", "Samarqand"], i=1, qiymat="Toshkent"
Chiqarish: ["Allamurod", "Toshkent"]
```

**Misol 2:**

```Python
Kirish: royxat=["Allamurod", "Samarqand"], i=5, qiymat="Toshkent"
Chiqarish: ["Allamurod", "Samarqand"]
```

---

## List18

Allamurodning 2×2 o'lchamli jadvali — ro'yxat ichidagi ro'yxat berilgan. Bosh diagonal elementlari (`[0][0]` va `[1][1]`) yig'indisini qaytaring.

**Misol 1:**

```Python
Kirish: jadval=[[1, 2], [3, 4]]
Chiqarish: 5
```

**Misol 2:**

```Python
Kirish: jadval=[[26, 0], [0, 74]]
Chiqarish: 100
```

---

## List19

Allamurodning 5 kunlik sport jadvali berilgan: 1 — sport zaliga bordi, 0 — bormadi. Allamurod necha kun sportga borganini `while` sikli va indekslar yordamida hisoblab qaytaring.

**Misol 1:**

```Python
Kirish: royxat=[1, 0, 1, 1, 0]
Chiqarish: 3
```

**Misol 2:**

```Python
Kirish: royxat=[0, 0, 0, 0, 0]
Chiqarish: 0
```

---

## List20

Allamurodning xaridlari ikki ro'yxat bilan berilgan: narxlar va soni (har biri 3 elementli). Indekslar orqali jami xarajatni hisoblab qaytaring.

**Misol 1:**

```Python
Kirish: narxlar=[12000, 3000, 95000], soni=[3, 4, 1]
Chiqarish: 143000
```

