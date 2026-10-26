---
title: ILineFillFormatEffectiveData
second_title: Referensi API Aspose.Slides untuk Java
description: Objek tak dapat diubah yang berisi properti pengisian garis yang efektif.
type: docs
url: /id/com.aspose.slides/ilinefillformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Objek tak dapat diubah yang berisi properti pengisian baris yang efektif.

--------------------

Antarmuka ini digunakan sebagai bagian dari [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFillType()](#getFillType--) | Mengembalikan tipe isi. |
| [getSolidFillColor()](#getSolidFillColor--) | Mengembalikan warna pengisian solid. |
| [getGradientFormat()](#getGradientFormat--) | Mengembalikan format pengisian gradien. |
| [getPatternFormat()](#getPatternFormat--) | Mengembalikan format pengisian pola. |
| [getRotateWithShape()](#getRotateWithShape--) | Menentukan apakah isi harus diputar bersama bentuk. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Mengembalikan tipe isi. Hanya-baca [FillType](../../com.aspose.slides/filltype).

**Mengembalikan:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```


Mengembalikan warna pengisian solid. Hanya-baca java.awt.Color.

**Mengembalikan:**
java.awt.Color
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
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Menentukan apakah isi harus diputar bersama bentuk. Hanya-baca boolean.

**Mengembalikan:**
boolean