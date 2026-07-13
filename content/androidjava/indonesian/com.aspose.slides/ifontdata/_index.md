---
title: IFontData
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a font definition.
type: docs
url: /id/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Mewakili definisi font.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFontName()](#getFontName--) | Mengembalikan nama font. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Mengembalikan nama font, menggantikan referensi tema dengan font aktual yang digunakan. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Mengembalikan nama font. String hanya-baca.

**Mengembalikan:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```


Mengembalikan nama font, menggantikan referensi tema dengan font aktual yang digunakan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Tema dari mana nama font bertema harus diambil. Terserah pemanggil untuk memberikan nilai yang benar. |

**Mengembalikan:**
java.lang.String - Nama font.