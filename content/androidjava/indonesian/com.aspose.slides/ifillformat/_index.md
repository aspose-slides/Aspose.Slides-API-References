---
title: IFillFormat
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili opsi format isian.
type: docs
url: /id/com.aspose.slides/ifillformat/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

Mewakili opsi format isian.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFillType()](#getFillType--) | Mengembalikan atau mengatur tipe pengisian. |
| [setFillType(byte value)](#setFillType-byte-) | Mengembalikan atau mengatur tipe pengisian. |
| [getSolidFillColor()](#getSolidFillColor--) | Mengembalikan warna isian. |
| [getGradientFormat()](#getGradientFormat--) | Mengembalikan format isian gradasi. |
| [getPatternFormat()](#getPatternFormat--) | Mengembalikan format isian pola. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Mengembalikan format isian gambar. |
| [getRotateWithShape()](#getRotateWithShape--) | Menentukan apakah isian harus diputar bersama bentuk. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Menentukan apakah isian harus diputar bersama bentuk. |
| [getEffective()](#getEffective--) | Mendapatkan data format isian yang efektif dengan pewarisan yang diterapkan. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Mengembalikan atau mengatur tipe pengisian. Baca/tulis [FillType](../../com.aspose.slides/filltype).

**Mengembalikan:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```


Mengembalikan atau mengatur tipe pengisian. Baca/tulis [FillType](../../com.aspose.slides/filltype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```


Mengembalikan warna isian. Baca saja [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


Mengembalikan format isian gradasi. Baca saja [IGradientFormat](../../com.aspose.slides/igradientformat).

**Mengembalikan:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


Mengembalikan format isian pola. Baca saja [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Mengembalikan:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```


Mengembalikan format isian gambar. Baca saja [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Mengembalikan:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
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

### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```


Mendapatkan data format isian yang efektif dengan pewarisan yang diterapkan.

**Mengembalikan:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - Sebuah [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).