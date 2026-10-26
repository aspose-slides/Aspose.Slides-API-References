---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective paragraph formatting properties.
type: docs
url: /id/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

Objek tak dapat diubah yang berisi properti pemformatan paragraf yang efektif.

--------------------

Antarmuka ini digunakan bersama dengan antarmuka [IParagraphFormat](../../com.aspose.slides/iparagraphformat) untuk mengembalikan nilai pemformatan yang efektif dengan pewarisan diterapkan.
## Metode

| Method | Description |
| --- | --- |
| [getBullet()](#getBullet--) | Mengembalikan format bullet dari sebuah paragraf. |
| [getDepth()](#getDepth--) | Mengembalikan kedalaman sebuah paragraf. |
| [getAlignment()](#getAlignment--) | Mengembalikan perataan teks dalam sebuah paragraf. |
| [getSpaceWithin()](#getSpaceWithin--) | Mengembalikan jumlah ruang antara garis dasar dalam sebuah paragraf. |
| [getSpaceBefore()](#getSpaceBefore--) | Mengembalikan jumlah ruang sebelum baris pertama dalam sebuah paragraf. |
| [getSpaceAfter()](#getSpaceAfter--) | Mengembalikan jumlah ruang setelah baris terakhir dalam sebuah paragraf. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Menentukan apakah jeda baris Asia Timur digunakan dalam sebuah paragraf. |
| [getRightToLeft()](#getRightToLeft--) | Menentukan apakah penulisan dari kanan ke kiri digunakan dalam sebuah paragraf. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Menentukan apakah jeda baris Latin digunakan dalam sebuah paragraf. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Menentukan apakah tanda baca menggantung digunakan dalam sebuah paragraf. |
| [getMarginLeft()](#getMarginLeft--) | Mengembalikan margin kiri dalam sebuah paragraf. |
| [getMarginRight()](#getMarginRight--) | Mengembalikan margin kanan dalam sebuah paragraf. |
| [getIndent()](#getIndent--) | Mengembalikan Inden Baris Pertama/Inden Menggantung paragraf. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Mengembalikan ukuran tabulasi default. |
| [getTabs()](#getTabs--) | Mengembalikan tabulasi dalam sebuah paragraf. |
| [getFontAlignment()](#getFontAlignment--) | Mengembalikan perataan font dalam sebuah paragraf. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Mengembalikan format bagian default dari sebuah paragraf. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```

Mengembalikan format bullet dari sebuah paragraf. Baca-saja [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**Mengembalikan:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Mengembalikan kedalaman sebuah paragraf. Baca-saja short.

**Mengembalikan:**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Mengembalikan perataan teks dalam sebuah paragraf. Baca-saja [TextAlignment](../../com.aspose.slides/textalignment).

**Mengembalikan:**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Mengembalikan jumlah ruang antara garis dasar dalam sebuah paragraf. Baca-saja float.

**Mengembalikan:**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Mengembalikan jumlah ruang sebelum baris pertama dalam sebuah paragraf. Baca-saja float.

**Mengembalikan:**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Mengembalikan jumlah ruang setelah baris terakhir dalam sebuah paragraf. Baca-saja float.

**Mengembalikan:**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```

Menentukan apakah jeda baris Asia Timur digunakan dalam sebuah paragraf. Baca-saja boolean.

**Mengembalikan:**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Menentukan apakah penulisan dari kanan ke kiri digunakan dalam sebuah paragraf. Baca-saja boolean.

**Mengembalikan:**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```

Menentukan apakah jeda baris Latin digunakan dalam sebuah paragraf. Baca-saja boolean.

**Mengembalikan:**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```

Menentukan apakah tanda baca menggantung digunakan dalam sebuah paragraf. Baca-saja boolean.

**Mengembalikan:**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Mengembalikan margin kiri dalam sebuah paragraf. Baca-saja float.

**Mengembalikan:**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Mengembalikan margin kanan dalam sebuah paragraf. Baca-saja float.

**Mengembalikan:**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Mengembalikan Inden Baris Pertama/Inden Menggantung paragraf. Inden Menggantung dapat didefinisikan dengan nilai negatif. Baca-saja float.

**Mengembalikan:**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Mengembalikan ukuran tabulasi default. Baca-saja float.

**Mengembalikan:**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```

Mengembalikan tabulasi dalam sebuah paragraf. Baca-saja ITabEffectiveData[].

**Mengembalikan:**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Mengembalikan perataan font dalam sebuah paragraf. Baca-saja [FontAlignment](../../com.aspose.slides/fontalignment).

**Mengembalikan:**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```

Mengembalikan format bagian default dari sebuah paragraf. Baca-saja [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**Mengembalikan:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)