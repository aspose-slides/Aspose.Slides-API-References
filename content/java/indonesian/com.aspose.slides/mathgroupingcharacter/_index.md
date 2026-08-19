---
title: MathGroupingCharacter
second_title: Referensi API Aspose.Slides untuk Java
description: Menentukan simbol pengelompokan di atas atau di bawah sebuah ekspresi, biasanya untuk menyoroti hubungan antara elemen
type: docs
url: /id/com.aspose.slides/mathgroupingcharacter/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathGroupingCharacter extends MathElementBase implements IMathGroupingCharacter, IHasControlCharacterProperties
```

Menentukan simbol pengelompokkan di atas atau di bawah sebuah ekspresi, biasanya untuk menyoroti hubungan antara elemen

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | Menginisialisasi sebuah instance baru dari kelas MathGroupingCharacter dengan karakter pengelompokkan default U+23DF (BOTTOM CURLY BRACKET) |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Menginisialisasi sebuah instance baru dari kelas MathGroupingCharacter. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBase()](#getBase--) | Argumen dasar |
| [getCharacter()](#getCharacter--) | Karakter Pengelompokkan Nilai default: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Karakter Pengelompokkan Nilai default: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Posisi karakter pengelompokkan. |
| [setPosition(int value)](#setPosition-int-) | Posisi karakter pengelompokkan. |
| [getVerticalJustification()](#getVerticalJustification--) | Justifikasi vertikal karakter grup. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Justifikasi vertikal karakter grup. |
| [getChildren()](#getChildren--) | Mendapatkan elemen anak |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Properti Karakter Kontrol |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```

Menginisialisasi sebuah instance baru dari kelas MathGroupingCharacter dengan karakter pengelompokkan default U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Elemen dasar tempat bar diterapkan |

### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

Menginisialisasi sebuah instance baru dari kelas MathGroupingCharacter.

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Elemen dasar tempat bar diterapkan |
| character | char | Karakter Pengelompokkan |
| position | int | Posisi karakter pengelompokkan |
| verticalJustification | int | Justifikasi vertikal karakter grup |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Argumen dasar

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```

Karakter Pengelompokkan Nilai default: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Kurung Bawah
> ```

**Mengembalikan:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

Karakter Pengelompokkan Nilai default: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Kurung Bawah
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Posisi karakter pengelompokkan. Default: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Mengembalikan:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Posisi karakter pengelompokkan. Default: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public final int getVerticalJustification()
```

Justifikasi vertikal karakter grup. Menentukan penjajaran objek terhadap baseline. Misalnya, ketika karakter grup berada di atas objek, Justifikasi Vertikal Top menandakan bahwa bagian atas objek berada pada baseline; ketika Justifikasi Vertikal diatur ke Bottom, bagian bawah objek berada pada baseline Default: Bottom untuk Position=Top, dan Top untuk Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingcharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Mengembalikan:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public final void setVerticalJustification(int value)
```

Justifikasi vertikal karakter grup. Menentukan penjajaran objek terhadap baseline. Misalnya, ketika karakter grup berada di atas objek, Justifikasi Vertikal Top menandakan bahwa bagian atas objek berada pada baseline; ketika Justifikasi Vertikal diatur ke Bottom, bagian bawah objek berada pada baseline Default: Bottom untuk Position=Top, dan Top untuk Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

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