---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Objek tidak dapat diubah yang berisi properti format paragraf yang efektif.
type: docs
url: /id/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

Objek tidak dapat diubah yang berisi properti format paragraf yang efektif.

--------------------

Antarmuka ini digunakan bersama dengan antarmuka [IParagraphFormat](../../com.aspose.slides/iparagraphformat) untuk mengembalikan nilai format efektif dengan pewarisan diterapkan.
## Metode

| Method | Description |
| --- | --- |
| [getBullet()](#getBullet--) | Mengembalikan format bullet dari sebuah paragraf. |
| [getDepth()](#getDepth--) | Mengembalikan kedalaman sebuah paragraf. |
| [getAlignment()](#getAlignment--) | Mengembalikan perataan teks dalam sebuah paragraf. |
| [getSpaceWithin()](#getSpaceWithin--) | Mengembalikan jumlah ruang antara baris dasar dalam sebuah paragraf. |
| [getSpaceBefore()](#getSpaceBefore--) | Mengembalikan jumlah ruang sebelum baris pertama dalam sebuah paragraf. |
| [getSpaceAfter()](#getSpaceAfter--) | Mengembalikan jumlah ruang setelah baris terakhir dalam sebuah paragraf. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Menentukan apakah pemutusan baris Asia Timur digunakan dalam sebuah paragraf. |
| [getRightToLeft()](#getRightToLeft--) | Menentukan apakah penulisan Right to Left digunakan dalam sebuah paragraf. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Menentukan apakah pemutusan baris Latin digunakan dalam sebuah paragraf. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Menentukan apakah tanda baca gantung digunakan dalam sebuah paragraf. |
| [getMarginLeft()](#getMarginLeft--) | Mengembalikan margin kiri dalam sebuah paragraf. |
| [getMarginRight()](#getMarginRight--) | Mengembalikan margin kanan dalam sebuah paragraf. |
| [getIndent()](#getIndent--) | Mengembalikan Indent Baris Pertama/Hanging Indent paragraf. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Mengembalikan ukuran tabulasi default. |
| [getTabs()](#getTabs--) | Mengembalikan tabulasi sebuah paragraf. |
| [getFontAlignment()](#getFontAlignment--) | Mengembalikan perataan font dalam sebuah paragraf. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Mengembalikan format bagian default sebuah paragraf. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```


Mengembalikan format bullet dari sebuah paragraf. Hanya-baca [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**Mengembalikan:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```


Mengembalikan kedalaman sebuah paragraf. Hanya-baca short.

**Mengembalikan:**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Mengembalikan perataan teks dalam sebuah paragraf. Hanya-baca [TextAlignment](../../com.aspose.slides/textalignment).

**Mengembalikan:**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```


Mengembalikan jumlah ruang antara baris dasar dalam sebuah paragraf. Hanya-baca float.

**Mengembalikan:**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```


Mengembalikan jumlah ruang sebelum baris pertama dalam sebuah paragraf. Hanya-baca float.

**Mengembalikan:**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```


Mengembalikan jumlah ruang setelah baris terakhir dalam sebuah paragraf. Hanya-baca float.

**Mengembalikan:**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```


Menentukan apakah pemutusan baris Asia Timur digunakan dalam sebuah paragraf. Hanya-baca boolean.

**Mengembalikan:**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```


Menentukan apakah penulisan Right to Left digunakan dalam sebuah paragraf. Hanya-baca boolean.

**Mengembalikan:**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```


Menentukan apakah pemutusan baris Latin digunakan dalam sebuah paragraf. Hanya-baca boolean.

**Mengembalikan:**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```


Menentukan apakah tanda baca gantung digunakan dalam sebuah paragraf. Hanya-baca boolean.

**Mengembalikan:**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```


Mengembalikan margin kiri dalam sebuah paragraf. Hanya-baca float.

**Mengembalikan:**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```


Mengembalikan margin kanan dalam sebuah paragraf. Hanya-baca float.

**Mengembalikan:**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```


Mengembalikan Indent Baris Pertama/Hanging Indent paragraf. Hanging Indent dapat didefinisikan dengan nilai negatif. Hanya-baca float.

**Mengembalikan:**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```


Mengembalikan ukuran tabulasi default. Hanya-baca float.

**Mengembalikan:**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```


Mengembalikan tabulasi sebuah paragraf. Hanya-baca ITabEffectiveData[].

**Mengembalikan:**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```


Mengembalikan perataan font dalam sebuah paragraf. Hanya-baca [FontAlignment](../../com.aspose.slides/fontalignment).

**Mengembalikan:**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```


Mengembalikan format bagian default sebuah paragraf. Hanya-baca [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**Mengembalikan:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)