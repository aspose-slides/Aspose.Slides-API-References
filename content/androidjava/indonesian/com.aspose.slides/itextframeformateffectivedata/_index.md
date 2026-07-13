---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective text frame formatting properties.
type: docs
url: /id/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

Objek tak dapat diubah yang berisi properti pemformatan text frame yang efektif.

--------------------

Antarmuka ini digunakan bersama dengan antarmuka [ITextFrameFormat](../../com.aspose.slides/itextframeformat) untuk mengembalikan nilai format yang efektif dengan pewarisan yang diterapkan.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Mengembalikan gaya teks yang efektif. |
| [getMarginLeft()](#getMarginLeft--) | Mengembalikan margin kiri (points) dalam TextFrame. |
| [getMarginRight()](#getMarginRight--) | Mengembalikan margin kanan (points) dalam TextFrame. |
| [getMarginTop()](#getMarginTop--) | Mengembalikan margin atas (points) dalam TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Mengembalikan margin bawah (points) dalam TextFrame. |
| [getWrapText()](#getWrapText--) | Mengembalikan apakah teks dibungkus pada margin TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Mengembalikan teks jangkar vertikal dalam TextFrame. |
| [getCenterText()](#getCenterText--) | Mengembalikan apakah teks harus dipusatkan secara horizontal dalam kotak. |
| [getTextVerticalType()](#getTextVerticalType--) | Mengembalikan orientasi teks. |
| [getAutofitType()](#getAutofitType--) | Mengembalikan mode autofit teks. |
| [getColumnCount()](#getColumnCount--) | Menentukan jumlah kolom teks dalam persegi pembatas. |
| [getColumnSpacing()](#getColumnSpacing--) | Menentukan ruang antara kolom teks dalam area teks (dalam points). |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```


Mengembalikan gaya teks yang efektif. Hanya-baca [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**Mengembalikan:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


Mengembalikan margin kiri (points) dalam TextFrame. Hanya-baca double.

**Mengembalikan:**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


Mengembalikan margin kanan (points) dalam TextFrame. Hanya-baca double.

**Mengembalikan:**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


Mengembalikan margin atas (points) dalam TextFrame. Hanya-baca double.

**Mengembalikan:**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


Mengembalikan margin bawah (points) dalam TextFrame. Hanya-baca double.

**Mengembalikan:**
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```


Mengembalikan apakah teks dibungkus pada margin TextFrame. Hanya-baca boolean.

**Mengembalikan:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


Mengembalikan teks jangkar vertikal dalam TextFrame. Hanya-baca [TextAnchorType](../../com.aspose.slides/textanchortype).

**Mengembalikan:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```


Mengembalikan apakah teks harus dipusatkan secara horizontal dalam kotak. Hanya-baca boolean.

**Mengembalikan:**
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


Mengembalikan orientasi teks. Hanya-baca [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Mengembalikan:**
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


Mengembalikan mode autofit teks. Hanya-baca [TextAutofitType](../../com.aspose.slides/textautofittype).

**Mengembalikan:**
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


Menentukan jumlah kolom teks dalam persegi pembatas. Hanya-baca int.

**Mengembalikan:**
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```


Menentukan ruang antara kolom teks dalam area teks (dalam points). Hanya-baca float.

**Mengembalikan:**
float