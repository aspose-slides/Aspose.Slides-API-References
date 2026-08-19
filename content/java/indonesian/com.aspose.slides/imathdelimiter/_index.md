---
title: IMathDelimiter
second_title: Referensi API Aspose.Slides untuk Java
description: Menentukan objek delimiter yang terdiri dari karakter pembuka dan penutup seperti tanda kurung, kurung kurawal, kurung siku, dan batang vertikal, serta satu atau lebih elemen matematika di dalamnya yang dipisahkan oleh karakter yang ditentukan.
type: docs
url: /id/com.aspose.slides/imathdelimiter/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

Menentukan objek delimiter, yang terdiri dari karakter pembuka dan penutup (seperti tanda kurung, kurung kurawal, kurung siku, dan batang vertikal), serta satu atau lebih elemen matematika di dalamnya, dipisahkan oleh karakter yang ditentukan. Contoh: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

## Metode

| Method | Description |
| --- | --- |
| [getArguments()](#getArguments--) | Satu atau lebih elemen matematika dipisahkan oleh karakter delimiter |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character menentukan karakter pembatas awal, atau pembuka. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character menentukan karakter pembatas awal, atau pembuka. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character menentukan karakter yang memisahkan argumen dalam objek delimiter. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character menentukan karakter yang memisahkan argumen dalam objek delimiter. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character menentukan karakter pembatas akhir, atau penutup. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character menentukan karakter pembatas akhir, atau penutup. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Menentukan pertumbuhan BeginningCharacter, SeparatorCharacter, EndingCharacter. Ketika true, delimiter tumbuh secara vertikal untuk menyesuaikan tinggi operannya. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Menentukan pertumbuhan BeginningCharacter, SeparatorCharacter, EndingCharacter. Ketika true, delimiter tumbuh secara vertikal untuk menyesuaikan tinggi operannya. |
| [getDelimiterShape()](#getDelimiterShape--) | Menentukan bentuk delimiter dalam objek delimiter. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Menentukan bentuk delimiter dalam objek delimiter. |
| [delimit(char separatorCharacter)](#delimit-char-) | Membatasi argumen menggunakan karakter delimiter yang ditentukan |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```


Satu atau lebih elemen matematika dipisahkan oleh karakter delimiter

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


Delimiter Beginning Character menentukan karakter pembatas awal, atau pembuka. Delimiter matematika adalah karakter pembungkus seperti tanda kurung, kurung siku, dan kurung kurawal. Nilai default: '('.

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


Delimiter Beginning Character menentukan karakter pembatas awal, atau pembuka. Delimiter matematika adalah karakter pembungkus seperti tanda kurung, kurung siku, dan kurung kurawal. Nilai default: '('.

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


Delimiter Separator Character menentukan karakter yang memisahkan argumen dalam objek delimiter. Nilai default: '|'.

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
public abstract void setSeparatorCharacter(char value)
```


Delimiter Separator Character menentukan karakter yang memisahkan argumen dalam objek delimiter. Nilai default: '|'.

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


Delimiter Ending Character menentukan karakter pembatas akhir, atau penutup. Delimiter matematika adalah karakter pembungkus seperti tanda kurung, kurung siku, dan kurung kurawal. Nilai default: ')'.

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
public abstract void setEndingCharacter(char value)
```


Delimiter Ending Character menentukan karakter pembatas akhir, atau penutup. Delimiter matematika adalah karakter pembungkus seperti tanda kurung, kurung siku, dan kurung kurawal. Nilai default: ')'.

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
public abstract void setGrowToMatchOperandHeight(boolean value)
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
public abstract int getDelimiterShape()
```


Menentukan bentuk delimiter dalam objek delimiter. Ketika MathDelimiterShape.Centered, delimiter terpusat di sekitar sumbu matematika dari teks matematika dan masih dapat dibuat menyesuaikan seluruh tinggi kontennya. Ketika MathDelimiterShape.Match, tinggi dan bentuknya diubah agar tepat sesuai dengan kontennya.

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
public abstract void setDelimiterShape(int value)
```


Menentukan bentuk delimiter dalam objek delimiter. Ketika MathDelimiterShape.Centered, delimiter terpusat di sekitar sumbu matematika dari teks matematika dan masih dapat dibuat menyesuaikan seluruh tinggi kontennya. Ketika MathDelimiterShape.Match, tinggi dan bentuknya diubah agar tepat sesuai dengan kontennya.

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
public abstract IMathDelimiter delimit(char separatorCharacter)
```


Membatasi argumen menggunakan karakter delimiter yang ditentukan

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| separatorCharacter | char | karakter delimiter |

**Mengembalikan:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Objek ini setelah menerapkan karakter delimiter