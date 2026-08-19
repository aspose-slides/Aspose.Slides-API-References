---
title: MathDelimiter
second_title: Referensi API Aspose.Slides untuk Java
description: Menentukan objek delimiter yang terdiri dari karakter pembuka dan penutup seperti tanda kurung, kurung kurawal, kurung siku, dan batang vertikal, serta satu atau lebih elemen matematika di dalamnya yang dipisahkan oleh karakter tertentu.
type: docs
url: /id/com.aspose.slides/mathdelimiter/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

Menentukan objek delimiter, yang terdiri dari karakter pembuka dan penutup (seperti kurung, kurung kurawal, kurung siku, dan batang vertikal), serta satu atau lebih elemen matematika di dalamnya, dipisahkan oleh karakter yang ditentukan. Contoh: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

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
| [getArguments()](#getArguments--) | Satu atau lebih elemen matematika yang dipisahkan oleh karakter delimiter |
| [getBeginningCharacter()](#getBeginningCharacter--) | Karakter Awal Delimiter menentukan karakter delimiter awal, atau pembuka. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Karakter Awal Delimiter menentukan karakter delimiter awal, atau pembuka. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Karakter Pemisah Delimiter menentukan karakter yang memisahkan argumen dalam objek delimiter. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Karakter Pemisah Delimiter menentukan karakter yang memisahkan argumen dalam objek delimiter. |
| [getEndingCharacter()](#getEndingCharacter--) | Karakter Akhir Delimiter menentukan karakter delimiter akhir, atau penutup. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Karakter Akhir Delimiter menentukan karakter delimiter akhir, atau penutup. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Menentukan pertumbuhan BeginningCharacter, SeparatorCharacter, EndingCharacter. Ketika true, delimiter tumbuh secara vertikal untuk menyesuaikan tinggi operannya. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Menentukan pertumbuhan BeginningCharacter, SeparatorCharacter, EndingCharacter. Ketika true, delimiter tumbuh secara vertikal untuk menyesuaikan tinggi operannya. |
| [getDelimiterShape()](#getDelimiterShape--) | Menentukan bentuk delimiter dalam objek delimiter. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Menentukan bentuk delimiter dalam objek delimiter. |
| [delimit(char separatorCharacter)](#delimit-char-) | Membedakan argumen menggunakan karakter delimiter yang ditentukan |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Membungkus elemen matematika dalam karakter yang ditentukan seperti kurung atau karakter lain sebagai bingkai |
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
| element | [IMathElement](../../com.aspose.slides/imathelement) | Elemen dasar dimana delimiter diterapkan. Bisa null. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

Satu atau lebih elemen matematika yang dipisahkan oleh karakter delimiter

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

Karakter Awal Delimiter menentukan karakter delimiter awal, atau pembuka. Delimiter matematika adalah karakter pembungkus seperti kurung, tanda kurung siku, dan kurung kurawal. Nilai default: '('.

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

Karakter Awal Delimiter menentukan karakter delimiter awal, atau pembuka. Delimiter matematika adalah karakter pembungkus seperti kurung, tanda kurung siku, dan kurung kurawal. Nilai default: '('.

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

Karakter Pemisah Delimiter menentukan karakter yang memisahkan argumen dalam objek delimiter. Nilai default: '|'.

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

Karakter Pemisah Delimiter menentukan karakter yang memisahkan argumen dalam objek delimiter. Nilai default: '|'.

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

Karakter Akhir Delimiter menentukan karakter delimiter akhir, atau penutup. Delimiter matematika adalah karakter pembungkus seperti kurung, tanda kurung siku, dan kurung kurawal. Nilai default: ')'.

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

Karakter Akhir Delimiter menentukan karakter delimiter akhir, atau penutup. Delimiter matematika adalah karakter pembungkus seperti kurung, tanda kurung siku, dan kurung kurawal. Nilai default: ')'.

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

Menentukan pertumbuhan BeginningCharacter, SeparatorCharacter, EndingCharacter. Ketika true, delimiter tumbuh secara vertikal untuk menyesuaikan tinggi operannya. Nilai default adalah true

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

Menentukan pertumbuhan BeginningCharacter, SeparatorCharacter, EndingCharacter. Ketika true, delimiter tumbuh secara vertikal untuk menyesuaikan tinggi operannya. Nilai default adalah true

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

Menentukan bentuk delimiter dalam objek delimiter. Ketika MathDelimiterShape.Centered, delimiter berpusat di sekitar sumbu matematika teks dan masih dapat disesuaikan untuk menyesuaikan tinggi seluruh kontennya. Ketika MathDelimiterShape.Match, tinggi dan bentuknya diubah untuk tepat mencocokkan kontennya.

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

Menentukan bentuk delimiter dalam objek delimiter. Ketika MathDelimiterShape.Centered, delimiter berpusat di sekitar sumbu matematika teks dan masih dapat disesuaikan untuk menyesuaikan tinggi seluruh kontennya. Ketika MathDelimiterShape.Match, tinggi dan bentuknya diubah untuk tepat mencocokkan kontennya.

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

Membedakan argumen menggunakan karakter delimiter yang ditentukan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| separatorCharacter | char | karakter delimiter |

**Mengembalikan:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Objek ini setelah menerapkan karakter delimiter
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Membungkus elemen matematika dalam karakter yang ditentukan seperti kurung atau karakter lain sebagai bingkai

--------------------

> ```
> Example:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| beginningCharacter | char | Karakter awal (biasanya kurung kiri) |
| endingCharacter | char | Karakter akhir (biasanya kurung kanan) |

**Mengembalikan:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Jika beginningCharacter dan endingCharacter null, properti yang bersangkutan hanya diberikan nilai dan tidak dibuat objek baru (mengembalikan instance ini). Jika tidak, mengembalikan elemen matematika baru tipe Delimiter yang mencakup karakter yang ditentukan sebagai bingkai dan instance [MathDelimiter](../../com.aspose.slides/mathdelimiter) ini dibingkai di dalamnya.
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