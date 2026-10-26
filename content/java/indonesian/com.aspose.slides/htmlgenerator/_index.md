---
title: HtmlGenerator
second_title: Referensi API Aspose.Slides untuk Java
description: Generator HTML.
type: docs
url: /id/com.aspose.slides/htmlgenerator/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)
```
public final class HtmlGenerator implements IHtmlGenerator
```

Generator HTML.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Menambahkan teks HTML terformat. |
| [addHtml(char[] html)](#addHtml-char---) | Menambahkan teks HTML terformat. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Menambahkan teks HTML terformat. |
| [addText(String text)](#addText-java.lang.String-) | Menambahkan teks biasa ke file html, menggantikan karakter khusus dengan entitas html. |
| [addText(char[] text)](#addText-char---) | Menambahkan teks biasa ke file html, menggantikan karakter khusus dengan entitas html. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Menambahkan teks biasa ke file html, menggantikan karakter khusus dengan entitas html. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Menambahkan nilai atribut yang di-quote ke file html. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Menambahkan nilai atribut yang di-quote ke file html. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Menambahkan nilai atribut yang di-quote ke file html. |
| [getSlideImageSize()](#getSlideImageSize--) | Mengembalikan ukuran gambar slide. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Mengembalikan satuan di mana ukuran gambar slide ditentukan. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Mengembalikan kode CSS satuan di mana ukuran gambar slide ditentukan. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Mengembalikan indeks slide yang sebelumnya dirender atau -1 jika slide pertama sedang dirender. |
| [getSlideIndex()](#getSlideIndex--) | Mengembalikan indeks slide yang sedang dirender. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Mengembalikan indeks slide yang akan dirender setelah slide saat ini atau -1 jika slide terakhir sedang dirender. |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```

Menambahkan teks HTML terformat.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| html | java.lang.String | Teks yang akan ditambahkan. |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```

Menambahkan teks HTML terformat.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| html | char[] | Teks yang akan ditambahkan. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```

Menambahkan teks HTML terformat.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| html | char[] | Teks yang akan ditambahkan. |
| startIndex | int | Indeks mulai bagian yang akan ditambahkan. |
| length | int | Panjang bagian yang akan ditambahkan. |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```

Menambahkan teks biasa ke file html, menggantikan karakter khusus dengan entitas html. Baris baru dan spasi tidak diubah.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan ditambahkan. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```

Menambahkan teks biasa ke file html, menggantikan karakter khusus dengan entitas html. Baris baru dan spasi tidak diubah.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | char[] | Teks yang akan ditambahkan. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```

Menambahkan teks biasa ke file html, menggantikan karakter khusus dengan entitas html. Baris baru dan spasi tidak diubah.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | char[] | Teks yang akan ditambahkan. |
| startIndex | int | Indeks mulai bagian yang akan ditambahkan. |
| length | int | Panjang bagian yang akan ditambahkan. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```

Menambahkan nilai atribut yang di-quote ke file html.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String | String nilai atribut. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```

Menambahkan nilai atribut yang di-quote ke file html.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | char[] | String nilai atribut. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```

Menambahkan nilai atribut yang di-quote ke file html.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | char[] | String nilai atribut. |
| startIndex | int | Indeks mulai bagian yang akan ditambahkan. |
| length | int | Panjang bagian yang akan ditambahkan. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final Dimension2D getSlideImageSize()
```

Mengembalikan ukuran gambar slide. Hanya baca java.awt.geom.Dimension2D.

**Mengembalikan:**
java.awt.geom.Dimension2D

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```

Mengembalikan satuan di mana ukuran gambar slide ditentukan. Hanya baca [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Mengembalikan:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```

Mengembalikan kode CSS satuan di mana ukuran gambar slide ditentukan. Hanya baca String.

**Mengembalikan:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```

Mengembalikan indeks slide yang sebelumnya dirender atau -1 jika slide pertama sedang dirender. Hanya baca int.

**Mengembalikan:**
int

### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```

Mengembalikan indeks slide yang sedang dirender. Hanya baca int.

**Mengembalikan:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```

Mengembalikan indeks slide yang akan dirender setelah slide saat ini atau -1 jika slide terakhir sedang dirender. Hanya baca int.

**Mengembalikan:**
int