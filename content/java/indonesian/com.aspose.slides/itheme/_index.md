---
title: ITheme
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili sebuah tema.
type: docs
url: /id/com.aspose.slides/itheme/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

Mewakili sebuah tema.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Mengembalikan skema warna. |
| [getFontScheme()](#getFontScheme--) | Mengembalikan skema font. |
| [getFormatScheme()](#getFormatScheme--) | Mengembalikan skema format bentuk. |
| [getEffective()](#getEffective--) | Mendapatkan data tema yang efektif dengan pewarisan diterapkan. |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```


Mengembalikan skema warna. Hanya-baca [IColorScheme](../../com.aspose.slides/icolorscheme).

**Mengembalikan:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```


Mengembalikan skema font. Hanya-baca [IFontScheme](../../com.aspose.slides/ifontscheme).

**Mengembalikan:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```


Mengembalikan skema format bentuk. Hanya-baca [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Mengembalikan:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```


Mendapatkan data tema yang efektif dengan pewarisan diterapkan.

**Mengembalikan:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - A [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).