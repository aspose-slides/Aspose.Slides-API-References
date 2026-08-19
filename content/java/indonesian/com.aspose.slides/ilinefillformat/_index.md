---
title: ILineFillFormat
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili properti untuk pengisian garis.
type: docs
url: /id/com.aspose.slides/ilinefillformat/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

Mewakili properti untuk pengisian garis.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFillType()](#getFillType--) | Mengembalikan atau mengatur tipe isian. |
| [setFillType(byte value)](#setFillType-byte-) | Mengembalikan atau mengatur tipe isian. |
| [getSolidFillColor()](#getSolidFillColor--) | Mengembalikan warna isian padat. |
| [getGradientFormat()](#getGradientFormat--) | Mengembalikan format isian gradien. |
| [getPatternFormat()](#getPatternFormat--) | Mengembalikan format isian pola. |
| [getRotateWithShape()](#getRotateWithShape--) | Menentukan apakah isian harus diputar bersama bentuk. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Menentukan apakah isian harus diputar bersama bentuk. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Mengembalikan atau mengatur tipe isian. Baca/tulis [FillType](../../com.aspose.slides/filltype).

**Mengembalikan:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```


Mengembalikan atau mengatur tipe isian. Baca/tulis [FillType](../../com.aspose.slides/filltype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```


Mengembalikan warna isian padat. Baca-saja [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


Mengembalikan format isian gradien. Baca-saja [IGradientFormat](../../com.aspose.slides/igradientformat).

**Mengembalikan:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


Mengembalikan format isian pola. Baca-saja [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Mengembalikan:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```


Menentukan apakah isian harus diputar bersama bentuk. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```


Menentukan apakah isian harus diputar bersama bentuk. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |