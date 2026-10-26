---
title: LineFillFormat
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili properti untuk mengisi garis.
type: docs
url: /id/com.aspose.slides/linefillformat/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

Mewakili properti untuk mengisi garis.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Mengembalikan atau mengatur fill type. |
| [setFillType(byte value)](#setFillType-byte-) | Mengembalikan atau mengatur fill type. |
| [getRotateWithShape()](#getRotateWithShape--) | Menentukan apakah fill harus diputar bersama shape. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Menentukan apakah fill harus diputar bersama shape. |
| [getSolidFillColor()](#getSolidFillColor--) | Mengembalikan warna dari solid fill. |
| [getGradientFormat()](#getGradientFormat--) | Mengembalikan format gradient fill. |
| [getPatternFormat()](#getPatternFormat--) | Mengembalikan format pattern fill. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versi. Hanya-baca long.

**Mengembalikan:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```


Mengembalikan atau mengatur fill type. Baca/tulis [FillType](../../com.aspose.slides/filltype).

**Mengembalikan:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```


Mengembalikan atau mengatur fill type. Baca/tulis [FillType](../../com.aspose.slides/filltype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```


Menentukan apakah fill harus diputar bersama shape. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```


Menentukan apakah fill harus diputar bersama shape. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```


Mengembalikan warna dari solid fill. Hanya-baca [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```


Mengembalikan format gradient fill. Hanya-baca [IGradientFormat](../../com.aspose.slides/igradientformat).

**Mengembalikan:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```


Mengembalikan format pattern fill. Hanya-baca [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Mengembalikan:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)