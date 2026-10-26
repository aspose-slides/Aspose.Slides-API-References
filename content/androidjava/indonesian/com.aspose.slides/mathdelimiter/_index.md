---
title: MathDelimiter
second_title: Referensi API Java Aspose.Slides untuk Android
description: Menentukan objek pembatas yang terdiri dari karakter pembuka dan penutup seperti tanda kurung, kurung kurawal, kurung siku, dan garis vertikal, serta satu atau lebih elemen matematika di dalamnya yang dipisahkan oleh karakter yang ditentukan.
type: docs
url: /id/com.aspose.slides/mathdelimiter/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

Menentukan objek pembatas, yang terdiri dari karakter pembuka dan penutup (seperti tanda kurung, kurung kurawal, kurung siku, dan garis vertikal), serta satu atau lebih elemen matematika di dalamnya, dipisahkan oleh karakter yang ditentukan. Contoh: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | Menginisialisasi MathDelimiter dengan elemen yang ditentukan sebagai argumen dasar tunggal |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getArguments()](#getArguments--) | Satu atau lebih elemen matematika yang dipisahkan oleh karakter pembatas |
| [getBeginningCharacter()](#getBeginningCharacter--) | Karakter Awal Pembatas menentukan karakter pembatas awal, atau pembuka. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Karakter Awal Pembatas menentukan karakter pembatas awal, atau pembuka. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Karakter Pemisah Pembatas menentukan karakter yang memisahkan argumen dalam objek pembatas. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Karakter Pemisah Pembatas menentukan karakter yang memisahkan argumen dalam objek pembatas. |
| [getEndingCharacter()](#getEndingCharacter--) | Karakter Akhir Pembatas menentukan karakter pembatas akhir, atau penutup. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Karakter Akhir Pembatas menentukan karakter pembatas akhir, atau penutup. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Menentukan pertumbuhan BeginningCharacter, SeparatorCharacter, EndingCharacter. Ketika true, pembatas tumbuh secara vertikal untuk menyesuaikan tinggi operannya. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Menentukan pertumbuhan BeginningCharacter, SeparatorCharacter, EndingCharacter. Ketika true, pembatas tumbuh secara vertikal untuk menyesuaikan tinggi operannya. |
| [getDelimiterShape()](#getDelimiterShape--) | Menentukan bentuk pembatas dalam objek pembatas. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Menentukan bentuk pembatas dalam objek pembatas. |
| [delimit(char separatorCharacter)](#delimit-char-) | Membatasi argumen menggunakan karakter pembatas yang ditentukan |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Membungkus elemen matematika dalam karakter yang ditentukan seperti tanda kurung atau karakter lain sebagai bingkai |
| [getChildren()](#getChildren--) | Mendapatkan elemen anak |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Properti Karakter Kontrol |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```


Menginisialisasi MathDelimiter dengan elemen yang ditentukan sebagai argumen dasar tunggal

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Elemen dasar yang akan diberi pembatas. Dapat bernilai null. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```


Satu atau lebih elemen matematika yang dipisahkan oleh karakter pembatas

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**Mengembalikan:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public final char getBeginningCharacter()
```


Karakter Awal Pembatas menentukan karakter pembatas awal, atau pembuka. Pembatas matematika adalah karakter yang mengelilingi seperti tanda kurung, kurung siku, dan kurung kurawal. Nilai default: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```


**Mengembalikan:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public final void setBeginningCharacter(char value)
```


Karakter Awal Pembatas menentukan karakter pembatas awal, atau pembuka. Pembatas matematika adalah karakter yang mengelilingi seperti tanda kurung, kurung siku, dan kurung kurawal. Nilai default: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public final char getSeparatorCharacter()
```


Karakter Pemisah Pembatas menentukan karakter yang memisahkan argumen dalam objek pembatas. Nilai default: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Mengembalikan:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public final void setSeparatorCharacter(char value)
```


Karakter Pemisah Pembatas menentukan karakter yang memisahkan argumen dalam objek pembatas. Nilai default: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public final char getEndingCharacter()
```


Karakter Akhir Pembatas menentukan karakter pembatas akhir, atau penutup. Pembatas matematika adalah karakter yang mengelilingi seperti tanda kurung, kurung siku, dan kurung kurawal. Nilai default: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Mengembalikan:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public final void setEndingCharacter(char value)
```


Karakter Akhir Pembatas menentukan karakter pembatas akhir, atau penutup. Pembatas matematika adalah karakter yang mengelilingi seperti tanda kurung, kurung siku, dan kurung kurawal. Nilai default: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```


Menentukan pertumbuhan BeginningCharacter, SeparatorCharacter, EndingCharacter. Ketika true, pembatas tumbuh secara vertikal untuk menyesuaikan tinggi operannya. Nilai default adalah true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Mengembalikan:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```


Menentukan pertumbuhan BeginningCharacter, SeparatorCharacter, EndingCharacter. Ketika true, pembatas tumbuh secara vertikal untuk menyesuaikan tinggi operannya. Nilai default adalah true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public final int getDelimiterShape()
```


Menentukan bentuk pembatas dalam objek pembatas. Ketika bentuknya MathDelimiterShape.Centered, pembatas berada di tengah sumbu matematika teks dan masih dapat disesuaikan agar memenuhi seluruh tinggi kontennya. Ketika bentuknya MathDelimiterShape.Match, tinggi dan bentuknya diubah agar tepat mencocokkan kontennya.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Mengembalikan:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public final void setDelimiterShape(int value)
```


Menentukan bentuk pembatas dalam objek pembatas. Ketika bentuknya MathDelimiterShape.Centered, pembatas berada di tengah sumbu matematika teks dan masih dapat disesuaikan agar memenuhi seluruh tinggi kontennya. Ketika bentuknya MathDelimiterShape.Match, tinggi dan bentuknya diubah agar tepat mencocokkan kontennya.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```


Membatasi argumen menggunakan karakter pembatas yang ditentukan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| separatorCharacter | char | karakter pembatas |

**Mengembalikan:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Objek ini setelah menerapkan karakter pembatas
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```


Membungkus elemen matematika dalam karakter yang ditentukan seperti tanda kurung atau karakter lain sebagai bingkai

--------------------

> ```
> Contoh:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
>  ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| beginningCharacter | char | Karakter awal (biasanya kurung kiri) |
| endingCharacter | char | Karakter akhir (biasanya kurung kanan) |

**Mengembalikan:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Jika beginningCharacter dan endingCharacter bernilai null, properti yang bersangkutan hanya diberikan nilai dan tidak dibuat objek baru (mengembalikan instance ini). Jika tidak, mengembalikan elemen matematika baru tipe Delimiter yang mencakup karakter yang ditentukan sebagai bingkai dan instance [MathDelimiter](../../com.aspose.slides/mathdelimiter) ini dibungkus di dalamnya.
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Mendapatkan elemen anak

**Mengembalikan:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Properti Karakter Kontrol

**Mengembalikan:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps