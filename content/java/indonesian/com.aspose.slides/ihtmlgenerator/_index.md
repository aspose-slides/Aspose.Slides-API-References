---
title: IHtmlGenerator
second_title: Aspose.Slides for Java API Reference
description: Generator HTML.
type: docs
url: /id/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

Generator HTML.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Adds formatted HTML text. |
| [addHtml(char[] html)](#addHtml-char---) | Adds formatted HTML text. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Adds formatted HTML text. |
| [addText(String text)](#addText-java.lang.String-) | Adds plain text to the html files, replacing special characters with html entities. |
| [addText(char[] text)](#addText-char---) | Adds plain text to the html files, replacing special characters with html entities. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Adds plain text to the html files, replacing special characters with html entities. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Quotes attribute value and adds it to the html file. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Quotes attribute value and adds it to the html file. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Quotes attribute value and adds it to the html file. |
| [getSlideImageSize()](#getSlideImageSize--) | Returns slide image size. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Returns a unit in which slide image size is specified. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Returns a css code of unit in which slide image size is specified. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Returns index of previously rendered slide or -1 if first slide is rendering. |
| [getSlideIndex()](#getSlideIndex--) | Returns index of currently rendering slide. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Returns index of a slide, which will be rendered after the current slide or -1 if currently rendering last slide. |
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

Menambahkan teks biasa ke file html, menggantikan karakter khusus dengan entitas html. Baris baru dan spasi tidak diganti.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan ditambahkan. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

Menambahkan teks biasa ke file html, menggantikan karakter khusus dengan entitas html. Baris baru dan spasi tidak diganti.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | char[] | Teks yang akan ditambahkan. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

Menambahkan teks biasa ke file html, menggantikan karakter khusus dengan entitas html. Baris baru dan spasi tidak diganti.

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
public abstract Dimension2D getSlideImageSize()
```

Mengembalikan ukuran gambar slide. Hanya-baca java.awt.geom.Dimension2D.

**Mengembalikan:**
java.awt.geom.Dimension2D
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

Mengembalikan satuan di mana ukuran gambar slide ditentukan. Hanya-baca [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Mengembalikan:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

Mengembalikan kode CSS satuan di mana ukuran gambar slide ditentukan. Hanya-baca String.

**Mengembalikan:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

Mengembalikan indeks slide yang telah dirender sebelumnya atau -1 jika slide pertama sedang dirender. Hanya-baca int.

**Mengembalikan:**
int
### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```

Mengembalikan indeks slide yang sedang dirender. Hanya-baca int.

**Mengembalikan:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```

Mengembalikan indeks slide yang akan dirender setelah slide saat ini atau -1 jika slide terakhir sedang dirender. Hanya-baca int.

**Mengembalikan:**
int