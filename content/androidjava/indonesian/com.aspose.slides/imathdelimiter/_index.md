---
title: IMathDelimiter
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Menentukan objek pembatas yang terdiri dari karakter pembuka dan penutup seperti tanda kurung, kurung kurawal, kurung siku, dan garis vertikal, serta satu atau lebih elemen matematis di dalamnya yang dipisahkan oleh karakter yang ditentukan.
type: docs
url: /id/com.aspose.slides/imathdelimiter/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

Menentukan objek pembatas, yang terdiri dari karakter pembuka dan penutup (seperti kurung, kurung kurawal, kurung siku, dan garis vertikal), serta satu atau lebih elemen matematis di dalamnya, dipisahkan oleh karakter yang ditentukan. Contoh: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getArguments()](#getArguments--) | Satu atau lebih elemen matematis yang dipisahkan oleh karakter pembatas |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character menentukan karakter pembatas awal, atau pembuka. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character menentukan karakter pembatas awal, atau pembuka. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character menentukan karakter yang memisahkan argumen dalam objek pembatas. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character menentukan karakter yang memisahkan argumen dalam objek pembatas. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character menentukan karakter pembatas akhir, atau penutup. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character menentukan karakter pembatas akhir, atau penutup. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Menentukan pertumbuhan BeginningCharacter, SeparatorCharacter, EndingCharacter. Ketika true, pembatas tumbuh secara vertikal untuk menyesuaikan tinggi operandnya. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Menentukan pertumbuhan BeginningCharacter, SeparatorCharacter, EndingCharacter. Ketika true, pembatas tumbuh secara vertikal untuk menyesuaikan tinggi operandnya. |
| [getDelimiterShape()](#getDelimiterShape--) | Menentukan bentuk pembatas dalam objek pembatas. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Menentukan bentuk pembatas dalam objek pembatas. |
| [delimit(char separatorCharacter)](#delimit-char-) | Memisahkan argumen menggunakan karakter pembatas yang ditentukan |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Satu atau lebih elemen matematis yang dipisahkan oleh karakter pembatas

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
public abstract char getBeginningCharacter()
```

Delimiter Beginning Character menentukan karakter pembatas awal, atau pembuka. Delimiter matematis adalah karakter pembungkus seperti kurung, kurung siku, dan kurung kurawal. Nilai default: '('.

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
public abstract void setBeginningCharacter(char value)
```

Delimiter Beginning Character menentukan karakter pembatas awal, atau pembuka. Delimiter matematis adalah karakter pembungkus seperti kurung, kurung siku, dan kurung kurawal. Nilai default: '('.

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
public abstract char getSeparatorCharacter()
```

Delimiter Separator Character menentukan karakter yang memisahkan argumen dalam objek pembatas. Nilai default: '|'.

--------------------

> ```
> Contoh:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Mengembalikan:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public abstract void setSeparatorCharacter(char value)
```

Delimiter Separator Character menentukan karakter yang memisahkan argumen dalam objek pembatas. Nilai default: '|'.

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
public abstract char getEndingCharacter()
```

Delimiter Ending Character menentukan karakter pembatas akhir, atau penutup. Delimiter matematis adalah karakter pembungkus seperti kurung, kurung siku, dan kurung kurawal. Nilai default: ')'.

--------------------

> ```
> Contoh:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Mengembalikan:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public abstract void setEndingCharacter(char value)
```

Delimiter Ending Character menentukan karakter pembatas akhir, atau penutup. Delimiter matematis adalah karakter pembungkus seperti kurung, kurung siku, dan kurung kurawal. Nilai default: ')'.

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
public abstract boolean getGrowToMatchOperandHeight()
```

Menentukan pertumbuhan BeginningCharacter, SeparatorCharacter, EndingCharacter. Ketika true, pembatas tumbuh secara vertikal untuk menyesuaikan tinggi operandnya. Nilai default adalah true

--------------------

> ```
> Contoh:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
```

**Mengembalikan:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```

Menentukan pertumbuhan BeginningCharacter, SeparatorCharacter, EndingCharacter. Ketika true, pembatas tumbuh secara vertikal untuk menyesuaikan tinggi operandnya. Nilai default adalah true

--------------------

> ```
> Contoh:
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
public abstract int getDelimiterShape()
```

Menentukan bentuk pembatas dalam objek pembatas. Ketika MathDelimiterShape.Centered, pembatas berada di tengah sumbu matematika teks dan tetap disesuaikan untuk menampung seluruh tinggi kontennya. Ketika MathDelimiterShape.Match, tinggi dan bentuknya diubah agar tepat sesuai kontennya.

--------------------

> ```
> Contoh:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Mengembalikan:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public abstract void setDelimiterShape(int value)
```

Menentukan bentuk pembatas dalam objek pembatas. Ketika MathDelimiterShape.Centered, pembatas berada di tengah sumbu matematika teks dan tetap disesuaikan untuk menampung seluruh tinggi kontennya. Ketika MathDelimiterShape.Match, tinggi dan bentuknya diubah agar tepat sesuai kontennya.

--------------------

> ```
public abstract void setDelimiterShape(int value)
```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Memisahkan argumen menggunakan karakter pembatas yang ditentukan

--------------------

> ```
> Contoh:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| separatorCharacter | char | karakter pembatas |

**Mengembalikan:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Objek ini setelah menerapkan karakter pembatas