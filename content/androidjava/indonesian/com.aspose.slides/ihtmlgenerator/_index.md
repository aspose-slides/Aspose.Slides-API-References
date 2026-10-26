---
title: IHtmlGenerator
second_title: Aspose.Slides for Android via Java API Reference
description: Generator HTML.
type: docs
url: /id/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

Generator HTML.
## Metode

| Method | Description |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Menambahkan teks HTML terformat. |
| [addHtml(char[] html)](#addHtml-char---) | Menambahkan teks HTML terformat. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Menambahkan teks HTML terformat. |
| [addText(String text)](#addText-java.lang.String-) | Menambahkan teks biasa ke file html, menggantikan karakter khusus dengan entitas html. |
| [addText(char[] text)](#addText-char---) | Menambahkan teks biasa ke file html, menggantikan karakter khusus dengan entitas html. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Menambahkan teks biasa ke file html, menggantikan karakter khusus dengan entitas html. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Mengutip nilai atribut dan menambahkannya ke file html. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Mengutip nilai atribut dan menambahkannya ke file html. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Mengutip nilai atribut dan menambahkannya ke file html. |
| [getSlideImageSize()](#getSlideImageSize--) | Mengembalikan ukuran gambar slide. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Mengembalikan satuan di mana ukuran gambar slide ditentukan. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Mengembalikan kode CSS dari satuan di mana ukuran gambar slide ditentukan. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Mengembalikan indeks slide yang sebelumnya dirender atau -1 jika slide pertama sedang dirender. |
| [getSlideIndex()](#getSlideIndex--) | Mengembalikan indeks slide yang sedang dirender. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Mengembalikan indeks slide yang akan dirender setelah slide saat ini atau -1 jika slide terakhir sedang dirender. |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```


Menambahkan teks HTML terformat.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| html | java.lang.String | Teks yang akan ditambahkan. |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```


Menambahkan teks HTML terformat.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| html | char[] | Teks yang akan ditambahkan. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
```


Menambahkan teks HTML terformat.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| html | char[] | Teks yang akan ditambahkan. |
| startIndex | int | Indeks awal bagian yang akan ditambahkan. |
| length | int | Panjang bagian yang akan ditambahkan. |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```


Menambahkan teks biasa ke file html, menggantikan karakter khusus dengan entitas html. Pemecah baris dan spasi tidak diganti.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan ditambahkan. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```


Menambahkan teks biasa ke file html, menggantikan karakter khusus dengan entitas html. Pemecah baris dan spasi tidak diganti.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | char[] | Teks yang akan ditambahkan. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```


Menambahkan teks biasa ke file html, menggantikan karakter khusus dengan entitas html. Pemecah baris dan spasi tidak diganti.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | char[] | Teks yang akan ditambahkan. |
| startIndex | int | Indeks awal bagian yang akan ditambahkan. |
| length | int | Panjang bagian yang akan ditambahkan. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```


Mengutip nilai atribut dan menambahkannya ke file html.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String | String nilai atribut. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```


Mengutip nilai atribut dan menambahkannya ke file html.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | char[] | String nilai atribut. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```


Mengutip nilai atribut dan menambahkannya ke file html.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | char[] | String nilai atribut. |
| startIndex | int | Indeks awal bagian yang akan ditambahkan. |
| length | int | Panjang bagian yang akan ditambahkan. |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract SizeF getSlideImageSize()
```


Mengembalikan ukuran gambar slide. Baca-saja [SizeF](../../com.aspose.slides.android/sizef).

**Mengembalikan:**
[SizeF](../../com.aspose.slides.android/sizef)
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```


Mengembalikan satuan di mana ukuran gambar slide ditentukan. Baca-saja [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Mengembalikan:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```


Mengembalikan kode CSS dari satuan di mana ukuran gambar slide ditentukan. Baca-saja String.

**Mengembalikan:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```


Mengembalikan indeks slide yang sebelumnya dirender atau -1 jika slide pertama sedang dirender. Baca-saja int.

**Mengembalikan:**
int
### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```


Mengembalikan indeks slide yang sedang dirender. Baca-saja int.

**Mengembalikan:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```


Mengembalikan indeks slide yang akan dirender setelah slide saat ini atau -1 jika slide terakhir sedang dirender. Baca-saja int.

**Mengembalikan:**
int