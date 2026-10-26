---
title: FontData
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili definisi font.
type: docs
url: /id/com.aspose.slides/fontdata/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

Mewakili definisi font. Tidak dapat diubah.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Membuat objek FontData baru dengan nama font yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFontName()](#getFontName--) | Mengembalikan nama font. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Mengembalikan nama font, menggantikan referensi tema dengan font aktual yang digunakan. |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah dua instance FontData sama. |
| [hashCode()](#hashCode--) | Berfungsi sebagai fungsi hash untuk tipe tertentu, cocok untuk digunakan dalam algoritma hashing dan struktur data seperti tabel hash. |
| [toString()](#toString--) | Mengembalikan representasi string. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```


Membuat objek FontData baru dengan nama font yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | java.lang.String | Nama font. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Mengembalikan nama font. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```


Mengembalikan nama font, menggantikan referensi tema dengan font aktual yang digunakan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Tema dari mana nama font yang di-tema harus diambil. Terserah pemanggil untuk menyediakan nilai yang benar. Lihat [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Mengembalikan:**
java.lang.String - Nama font.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah dua instance FontData sama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | FontData yang dibandingkan dengan FontData saat ini. |

**Mengembalikan:**
boolean - **true** jika FontData yang ditentukan sama dengan FontData saat ini; bila tidak, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Berfungsi sebagai fungsi hash untuk tipe tertentu, cocok untuk digunakan dalam algoritma hashing dan struktur data seperti tabel hash.

**Mengembalikan:**
int - Kode hash dari FontData.
### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string.

**Mengembalikan:**
java.lang.String - Representasi string.