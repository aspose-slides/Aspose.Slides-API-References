---
title: ILineFillFormat
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili properti untuk pengisian garis.
type: docs
url: /id/com.aspose.slides/ilinefillformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

Mewakili properti untuk pengisian garis.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFillType()](#getFillType--) | Mengembalikan atau mengatur jenis pengisian. |
| [setFillType(byte value)](#setFillType-byte-) | Mengembalikan atau mengatur jenis pengisian. |
| [getSolidFillColor()](#getSolidFillColor--) | Mengembalikan warna pengisian solid. |
| [getGradientFormat()](#getGradientFormat--) | Mengembalikan format pengisian gradien. |
| [getPatternFormat()](#getPatternFormat--) | Mengembalikan format pengisian pola. |
| [getRotateWithShape()](#getRotateWithShape--) | Menentukan apakah pengisian harus diputar bersama bentuk. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Menentukan apakah pengisian harus diputar bersama bentuk. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Mengembalikan atau mengatur jenis pengisian. Baca/tulis [FillType](../../com.aspose.slides/filltype).

**Mengembalikan:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```


Mengembalikan atau mengatur jenis pengisian. Baca/tulis [FillType](../../com.aspose.slides/filltype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```


Mengembalikan warna pengisian solid. Baca-saja [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


Mengembalikan format pengisian gradien. Baca-saja [IGradientFormat](../../com.aspose.slides/igradientformat).

**Mengembalikan:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


Mengembalikan format pengisian pola. Baca-saja [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Mengembalikan:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```


Menentukan apakah pengisian harus diputar bersama bentuk. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```


Menentukan apakah pengisian harus diputar bersama bentuk. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |