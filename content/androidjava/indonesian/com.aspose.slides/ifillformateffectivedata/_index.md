---
title: IFillFormatEffectiveData
second_title: Referensi API Java Aspose.Slides untuk Android
description: Objek tidak dapat diubah yang berisi properti format pengisian efektif.
type: docs
url: /id/com.aspose.slides/ifillformateffectivedata/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

Objek tidak dapat diubah yang berisi properti format pengisian efektif.

--------------------

Antarmuka ini digunakan bersama dengan antarmuka [IFillFormat](../../com.aspose.slides/ifillformat) untuk mengembalikan nilai format efektif dengan pewarisan yang diterapkan.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFillType()](#getFillType--) | Mengembalikan jenis pengisian. |
| [getSolidFillColor()](#getSolidFillColor--) | Mengembalikan warna pengisian. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | Mendapatkan warna pengisian yang didefinisikan oleh skema warna. |
| [getGradientFormat()](#getGradientFormat--) | Mengembalikan format pengisian gradien. |
| [getPatternFormat()](#getPatternFormat--) | Mengembalikan format pengisian pola. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Mengembalikan format pengisian gambar. |
| [getRotateWithShape()](#getRotateWithShape--) | Menentukan apakah pengisian harus diputar bersama bentuk. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Mengembalikan jenis pengisian. Hanya-baca [FillType](../../com.aspose.slides/filltype).

**Mengembalikan:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```


Mengembalikan warna pengisian. Hanya-baca java.lang.Integer.

**Mengembalikan:**
java.lang.Integer
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```


Mendapatkan warna pengisian yang didefinisikan oleh skema warna. Nilai [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) menunjukkan bahwa SolidFillColor (\#getSolidFillColor.getSolidFillColor) bukan warna skema. Hanya-baca [SchemeColor](../../com.aspose.slides/schemecolor).

**Mengembalikan:**
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Mengembalikan format pengisian gradien. Hanya-baca [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Mengembalikan:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Mengembalikan format pengisian pola. Hanya-baca [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Mengembalikan:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```


Mengembalikan format pengisian gambar. Hanya-baca [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**Mengembalikan:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Menentukan apakah pengisian harus diputar bersama bentuk. Hanya-baca boolean.

**Mengembalikan:**
boolean