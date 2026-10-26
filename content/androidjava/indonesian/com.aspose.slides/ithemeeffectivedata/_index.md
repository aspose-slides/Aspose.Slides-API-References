---
title: IThemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Objek tidak dapat diubah yang berisi properti tema yang efektif.
type: docs
url: /id/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Objek tidak dapat diubah yang berisi properti tema yang efektif.

--------------------

Antarmuka ini digunakan bersama dengan antarmuka [ITheme](../../com.aspose.slides/itheme) untuk mengembalikan nilai format yang efektif dengan penerapan pewarisan.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getColorScheme(Integer styleColor)](#getColorScheme-java.lang.Integer-) | Mengembalikan skema warna. |
| [getFontScheme()](#getFontScheme--) | Mengembalikan skema font. |
| [getFormatScheme()](#getFormatScheme--) | Mengembalikan skema format bentuk. |

### getColorScheme(Integer styleColor) {#getColorScheme-java.lang.Integer-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Integer styleColor)
```

Mengembalikan skema warna.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| styleColor | java.lang.Integer | Warna java.lang.Integer |

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