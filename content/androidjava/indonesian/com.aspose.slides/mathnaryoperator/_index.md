---
title: MathNaryOperator
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Menentukan objek matematika N-ary seperti Penjumlahan dan Integral.
type: docs
url: /id/com.aspose.slides/mathnaryoperator/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

Menentukan objek matematika N-ary, seperti Penjumlahan dan Integral. Itu terdiri dari operator, basis (atau operand), dan batas atas serta bawah opsional. Contoh operator N-ary meliputi: Penjumlahan, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Menginisialisasi instance baru dari kelas MathNaryOperator. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Menginisialisasi instance baru dari kelas MathNaryOperator. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#MathNaryOperator-char-com.aspose.slides.IMathElement-) | Menginisialisasi instance baru dari kelas MathNaryOperator. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBase()](#getBase--) | Argumen basis |
| [getSubscript()](#getSubscript--) | Menentukan argumen subskrip yang, misalnya, dalam kasus integral, menetapkan batas bawah |
| [getSuperscript()](#getSuperscript--) | Menentukan argumen superskrip yang, misalnya, dalam kasus integral, menetapkan batas atas |
| [getOperator()](#getOperator--) | Karakter Operator N-ary, misalnya: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Karakter Operator N-ary, misalnya: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | Lokasi batas (subskrip dan superskrip) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | Lokasi batas (subskrip dan superskrip) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Karakter Operator tumbuh secara vertikal untuk menyesuaikan tinggi operandenya |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Karakter Operator tumbuh secara vertikal untuk menyesuaikan tinggi operandenya |
| [getHideSubscript()](#getHideSubscript--) | Sembunyikan Subskrip |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Sembunyikan Subskrip |
| [getHideSuperscript()](#getHideSuperscript--) | Sembunyikan Superskrip |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Sembunyikan Superskrip |
| [getChildren()](#getChildren--) | Dapatkan elemen anak |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Properti Karakter Kontrol |
### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Menginisialisasi instance baru dari kelas MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i=0"), new MathematicalText("\ud835\udc5b"));
```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| operatorSymbol | char | Simbol operator N-ary |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumen basis |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Batas bawah |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Batas atas |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Menginisialisasi instance baru dari kelas MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i"));
```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| operatorSymbol | char | Simbol operator N-ary |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumen basis |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Batas bawah |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#MathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Menginisialisasi instance baru dari kelas MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"));
```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| operatorSymbol | char | Simbol operator N-ary |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumen basis |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Argumen basis

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
```

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```


Menentukan argumen subskrip yang, misalnya, dalam kasus integral, menetapkan batas bawah

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```


Menentukan argumen superskrip yang, misalnya, dalam kasus integral, menetapkan batas atas

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperator() {#getOperator--}
```
public final char getOperator()
```


Karakter Operator N-ary, misalnya: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Mengembalikan:**
char
### setOperator(char value) {#setOperator-char-}
```
public final void setOperator(char value)
```


Karakter Operator N-ary, misalnya: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public final int getLimitLocation()
```


Lokasi batas (subskrip dan superskrip)

--------------------

> ```
> Contoh:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Mengembalikan:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public final void setLimitLocation(int value)
```


Lokasi batas (subskrip dan superskrip)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```


Karakter Operator tumbuh secara vertikal untuk menyesuaikan tinggi operandenya

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Mengembalikan:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```


Karakter Operator tumbuh secara vertikal untuk menyesuaikan tinggi operandenya

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public final boolean getHideSubscript()
```


Sembunyikan Subskrip

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Mengembalikan:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public final void setHideSubscript(boolean value)
```


Sembunyikan Subskrip

--------------------

> ```
> Contoh:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public final boolean getHideSuperscript()
```


Sembunyikan Superskrip

--------------------

> ```
> Contoh:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Mengembalikan:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public final void setHideSuperscript(boolean value)
```


Sembunyikan Superskrip

--------------------

> ```
> Contoh:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Dapatkan elemen anak

**Mengembalikan:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Properti Karakter Kontrol

**Mengembalikan:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps