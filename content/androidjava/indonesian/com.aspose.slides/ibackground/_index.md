---
title: IBackground
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili latar belakang slide.
type: docs
url: /id/com.aspose.slides/ibackground/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

Mewakili latar belakang slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getType()](#getType--) | Mengembalikan tipe pengisian latar belakang. |
| [setType(byte value)](#setType-byte-) | Mengembalikan tipe pengisian latar belakang. |
| [getFillFormat()](#getFillFormat--) | Mengembalikan FillFormat untuk pengisian BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | Mengembalikan EffectFormat untuk pengisian BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | Mengembalikan ColorFormat untuk pengisian BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | Mengembalikan indeks pengisian BackgroundType.Themed dalam koleksi tema latar belakang. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Mengembalikan indeks pengisian BackgroundType.Themed dalam koleksi tema latar belakang. |
| [getEffective()](#getEffective--) | Mendapatkan data latar belakang efektif dengan pewarisan yang diterapkan. |
### getType() {#getType--}
```
public abstract byte getType()
```

Mengembalikan tipe pengisian latar belakang. Baca/tulis [BackgroundType](../../com.aspose.slides/backgroundtype).

**Mengembalikan:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Mengembalikan tipe pengisian latar belakang. Baca/tulis [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Mengembalikan FillFormat untuk pengisian BackgroundType.OwnBackground. Baca-saja [IFillFormat](../../com.aspose.slides/ifillformat).

**Mengembalikan:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Mengembalikan EffectFormat untuk pengisian BackgroundType.OwnBackground. Baca-saja [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Mengembalikan:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```

Mengembalikan ColorFormat untuk pengisian BackgroundType.Themed. Baca-saja [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```

Mengembalikan indeks pengisian BackgroundType.Themed dalam koleksi tema latar belakang. 0 berarti tidak ada isian. 1..999 - indeks. Baca/tulis int.

**Mengembalikan:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```

Mengembalikan indeks pengisian BackgroundType.Themed dalam koleksi tema latar belakang. 0 berarti tidak ada isian. 1..999 - indeks. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```

Mendapatkan data latar belakang efektif dengan pewarisan yang diterapkan.

**Mengembalikan:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).