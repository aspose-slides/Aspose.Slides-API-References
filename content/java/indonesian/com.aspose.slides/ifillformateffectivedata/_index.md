---
title: IFillFormatEffectiveData
second_title: Referensi API Aspose.Slides untuk Java
description: Objek tidak dapat diubah yang berisi properti format isian efektif.
type: docs
url: /id/com.aspose.slides/ifillformateffectivedata/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

Objek tidak dapat diubah yang berisi properti format isian efektif.

--------------------

Antarmuka ini digunakan bersama dengan antarmuka [IFillFormat](../../com.aspose.slides/ifillformat) untuk mengembalikan nilai format efektif dengan pewarisan yang diterapkan.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFillType()](#getFillType--) | Mengembalikan tipe isian. |
| [getSolidFillColor()](#getSolidFillColor--) | Mengembalikan warna isian. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | Mendapatkan warna isian yang didefinisikan oleh skema warna. |
| [getGradientFormat()](#getGradientFormat--) | Mengembalikan format isian gradien. |
| [getPatternFormat()](#getPatternFormat--) | Mengembalikan format isian pola. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Mengembalikan format isian gambar. |
| [getRotateWithShape()](#getRotateWithShape--) | Menentukan apakah isian harus diputar bersama bentuk. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Mengembalikan tipe isian. Hanya-baca [FillType](../../com.aspose.slides/filltype).

**Mengembalikan:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```

Mengembalikan warna isian. Hanya-baca java.awt.Color.

**Mengembalikan:**
java.awt.Color
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```

Mendapatkan warna isian yang didefinisikan oleh skema warna. Nilai [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) menunjukkan bahwa SolidFillColor (\#getSolidFillColor.getSolidFillColor) bukan warna skema. Hanya-baca [SchemeColor](../../com.aspose.slides/schemecolor).

**Mengembalikan:**
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```

Mengembalikan format isian gradien. Hanya-baca [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Mengembalikan:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```

Mengembalikan format isian pola. Hanya-baca [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Mengembalikan:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```

Mengembalikan format isian gambar. Hanya-baca [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**Mengembalikan:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

Menentukan apakah isian harus diputar bersama bentuk. Hanya-baca boolean.

**Mengembalikan:**
boolean