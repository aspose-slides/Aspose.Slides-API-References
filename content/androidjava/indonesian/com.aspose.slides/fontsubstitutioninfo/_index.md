---
title: FontSubstitutionInfo
second_title: Referensi API Java Aspose.Slides untuk Android
description: Struktur ini mewakili informasi tentang penggantian font ketika akan dirender.
type: docs
url: /id/com.aspose.slides/fontsubstitutioninfo/
---
**Pewarisan:**
java.lang.Object
```
public class FontSubstitutionInfo
```

Struktur ini mewakili informasi tentang penggantian font ketika akan dirender.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions())
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | Membuat sebuah instance dari kelas [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | Menunjukkan nama font sumber dalam presentasi. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | Menunjukkan nama font pengganti untuk font asli. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```

Membuat sebuah instance dari kelas [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| originFontName | java.lang.String | Nama font sumber dalam presentasi String |
| substFontName | java.lang.String | Nama font pengganti untuk font asli String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```

Menunjukkan nama font sumber dalam presentasi. Hanya-baca String

**Mengembalikan:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```

Menunjukkan nama font pengganti untuk font asli. Hanya-baca String

**Mengembalikan:**
java.lang.String