---
title: IMathGroupingCharacter
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Menentukan simbol pengelompokan di atas atau di bawah sebuah ekspresi, biasanya untuk menyoroti hubungan antar elemen
type: docs
url: /id/com.aspose.slides/imathgroupingcharacter/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

Menentukan simbol pengelompokan di atas atau di bawah sebuah ekspresi, biasanya untuk menyoroti hubungan antar elemen

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBase()](#getBase--) | Argumen dasar |
| [getCharacter()](#getCharacter--) | Karakter Pengelompokan Nilai default: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Karakter Pengelompokan Nilai default: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Posisi karakter pengelompokan. |
| [setPosition(int value)](#setPosition-int-) | Posisi karakter pengelompokan. |
| [getVerticalJustification()](#getVerticalJustification--) | Justifikasi vertikal karakter grup. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Justifikasi vertikal karakter grup. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
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
public abstract char getCharacter()
```

Karakter Pengelompokan Nilai default: U+23DF (BOTTOM CURLY BRACKET)

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
public abstract void setCharacter(char value)
```

Karakter Pengelompokan Nilai default: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Kurung Bawah
> ```


**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Posisi karakter pengelompokan. Default: Bottom

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
public abstract void setPosition(int value)
```

Posisi karakter pengelompokan. Default: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public abstract int getVerticalJustification()
```

Justifikasi vertikal karakter grup. Menentukan perataan objek terhadap garis dasar. Misalnya, ketika karakter grup berada di atas objek, VerticalJustification Top menandakan bahwa bagian atas objek berada pada garis dasar; ketika VerticalJustification diatur ke Bottom, bagian bawah objek berada pada garis dasar Default: Bottom untuk Position=Top, dan Top untuk Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```


**Mengembalikan:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```

Justifikasi vertikal karakter grup. Menentukan perataan objek terhadap garis dasar. Misalnya, ketika karakter grup berada di atas objek, VerticalJustification Top menandakan bahwa bagian atas objek berada pada garis dasar; ketika VerticalJustification diatur ke Bottom, bagian bawah objek berada pada garis dasar Default: Bottom untuk Position=Top, dan Top untuk Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | int |  |