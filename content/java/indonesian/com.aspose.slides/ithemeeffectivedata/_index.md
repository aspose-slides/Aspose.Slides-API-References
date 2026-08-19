---
title: IThemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Objek tak dapat diubah yang berisi properti tema yang efektif.
type: docs
url: /id/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Objek tak dapat diubah yang berisi properti tema yang efektif.

--------------------

Antarmuka ini digunakan bersama dengan antarmuka [ITheme](../../com.aspose.slides/itheme) untuk mengembalikan nilai pemformatan yang efektif dengan penerapan pewarisan.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getColorScheme(Color styleColor)](#getColorScheme-java.awt.Color-) | Mengembalikan skema warna. |
| [getFontScheme()](#getFontScheme--) | Mengembalikan skema font. |
| [getFormatScheme()](#getFormatScheme--) | Mengembalikan skema format bentuk. |

### getColorScheme(Color styleColor) {#getColorScheme-java.awt.Color-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Color styleColor)
```

Mengembalikan skema warna.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Mengembalikan:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - skema warna [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)

### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```

Mengembalikan skema font. Hanya-baca [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**Mengembalikan:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)

### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```

Mengembalikan skema format bentuk. Hanya-baca [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Mengembalikan:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)