# String vazifa
---

### 🟡 **Errors (1–5)**

**1.** Quyidagi koddagi xatoni toping va to‘g‘irlab ekranga “Hello” chiqarilsin.

```python
print("Hello)
```

Output:

```text
Hello
```

**2.** Quyidagi kodda nimaga error chiqadi? Dastur ishlashi uchun kodni to‘g‘irlab yozing.

```python
num = "5" + 3
print(num)
```

Output:

```text
8
```

**3.** Quyidagi kodda qanday xato mavjud? Kodni tuzating:

```python
a = 10
b = 0
print(a / b)
```

Output:

```text
Nolga bo‘lish mumkin emas!
```

**4.** Quyidagi kodda qavslar xatosi mavjud. To‘g‘irlab, “Diyorbek” matnini chiqaring:

```python
print("Diyorbek"
```

Output:

```text
Diyorbek
```

**5.** Quyidagi koddagi sintaksis xatosini bartaraf eting:

```python
print("Salom"
print("Dunyo")
```

Output:

```text
Salom
Dunyo
```

---

### 🟢 **String & String Operators (6–10)**

**6.** Foydalanuvchidan ism kiriting va unga “Assalomu alaykum” so‘zini qo‘shib chiqaring.
Output:

```text
Ismingizni kiriting: Ali
Assalomu alaykum Ali
```

**7.** Foydalanuvchidan familiya kiriting va `+` operatori orqali `“Familiyangiz: ”` matnini birlashtiring.
Output:

```text
Familiya kiriting: Karimov
Familiyangiz: Karimov
```

**8.** Foydalanuvchidan ikki so‘z kiriting va ular orasiga bo‘sh joy qo‘yib bitta matn holida chiqaring.
Output:

```text
Birinchi soʻz: Hello
Ikkinchi soʻz: World
Natija: Hello World
```

**9.** Foydalanuvchidan ism kiriting va ismning uzunligini (`len()`) chiqarib bering.
Output:

```text
Ism: Muhammad
Uzunligi: 8
```

**10.** Foydalanuvchidan bitta so‘z kiriting va uni 5 marta ketma-ket chiqarib bering.
Output:

```text
So‘z: hi
Natija: hihihihihi
```

---

### 🔵 **String Indexing & Slicing (11–15)**

**11.** Foydalanuvchidan so‘z kiriting. Shu so‘zning **birinchi harfini** chiqarib bering.
Output:

```text
So‘z kiriting: python
Birinchi harf: p
```

**12.** Foydalanuvchidan so‘z kiriting. Shu so‘zning **oxirgi harfini** chiqarib bering.
Output:

```text
So‘z kiriting: python
Oxirgi harf: n
```

**13.** Foydalanuvchidan so‘z kiriting va **3-harfdan boshlab oxirigacha** bo‘lgan qismini chiqaring.
Output:

```text
So‘z kiriting: programming
Natija: ogramming
```

**14.** Foydalanuvchidan so‘z kiriting va **0–4 indekslar orasidagi** bo‘lakni chop eting.
Output:

```text
So‘z kiriting: HelloWorld
Natija: Hell
```

**15.** Foydalanuvchidan uzunroq so‘z kiriting. So‘zning **har 2-harfini** chiqarib bering (`[::2]`).
Output:

```text
So‘z kiriting: programming
Natija: poramn
```

---

### 🟣 **String Formatting (16–20)**

**16.** Foydalanuvchidan ism va yosh kiriting va **f-string** yordamida quyidagicha formatda chiqarib bering.
Output:

```text
Ismingiz Ali, yoshingiz 20 da.
```

**17.** Foydalanuvchidan shahar nomi va indeks kiriting. **`.format()`** yordamida quyidagicha chiqarib bering.
Output:

```text
Shahar: Buxoro, Indeks: 200100
```

**18.** Foydalanuvchidan ism kiriting. F-string yordamida “Salom, \[ism]” shaklida chiqarib bering.
Output:

```text
Salom, Diyorbek
```

**19.** Foydalanuvchidan son (`float`) kiriting. F-string yordamida 2 xonagacha yaxlitlangan ko‘rinishda chiqarib bering (`:.2f`).
Output:

```text
Son kiriting: 5.6789
Yaxlitlangan: 5.68
```

**20.** Foydalanuvchidan uchta ma’lumot kiriting: ism, yosh va kasb. **`.format()`** yordamida quyidagi shaklda chiqaring:

```text
Ism: Ali | Yosh: 18 | Kasb: Student
```
