---
title: IParagraphCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili koleksi paragraf.
type: docs
url: /id/com.aspose.slides/iparagraphcollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

Mewakili koleksi paragraf.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengambil elemen pada indeks yang ditentukan. |
| [getCount()](#getCount--) | Mengambil jumlah elemen yang sebenarnya terdapat dalam koleksi. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Menambahkan Paragraph ke akhir koleksi. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Menambahkan konten ParagraphCollection ke akhir koleksi. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Menyisipkan Paragraph ke dalam koleksi pada indeks yang ditentukan. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Menyisipkan konten ParagraphCollection ke dalam koleksi pada indeks yang ditentukan. |
| [clear()](#clear--) | Menghapus semua elemen dari koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus elemen pada indeks yang ditentukan dalam koleksi. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Menghapus kejadian pertama dari paragraf tertentu. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Menambahkan teks dari string html yang ditentukan ke koleksi. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Menambahkan teks dari string html yang ditentukan ke koleksi. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Mengonversi paragraf yang ditentukan ke HTML dan mengembalikannya sebagai objek String. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```


Mengambil elemen pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IParagraph](../../com.aspose.slides/iparagraph)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Mengambil jumlah elemen yang sebenarnya terdapat dalam koleksi. Hanya-baca int.

**Mengembalikan:**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```


Menambahkan Paragraph ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph yang akan ditambahkan ke akhir koleksi. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```


Menambahkan konten ParagraphCollection ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | ParagraphCollection yang akan ditambahkan ke akhir koleksi. |

**Mengembalikan:**
int - Indeks tempat Paragraph ditambahkan atau -1 jika tidak ada yang dapat ditambahkan.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```


Menyisipkan Paragraph ke dalam koleksi pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dimana Paragraph harus disisipkan. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph yang akan disisipkan. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```


Menyisipkan konten ParagraphCollection ke dalam koleksi pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dimana paragraf harus disisipkan. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Paragraf yang akan disisipkan. |

### clear() {#clear--}
```
public abstract void clear()
```


Menghapus semua elemen dari koleksi.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Menghapus elemen pada indeks yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari elemen yang akan dihapus. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```


Menghapus kejadian pertama dari paragraf tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraf yang akan dihapus dari koleksi. |

**Mengembalikan:**
boolean - true jika item berhasil dihapus; sebaliknya, false.
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```


Menambahkan teks dari string html yang ditentukan ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```


Menambahkan teks dari string html yang ditentukan ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objek callback resolver yang menyelesaikan URI dan mengambil objek yang dirujuk. |
| uri | java.lang.String | URI untuk menambahkan dokumen HTML. Digunakan untuk menyelesaikan tautan relatif.

--------------------

Menentukan resolver dapat berpotensi memperkenalkan kerentanan. Gunakan dengan hati-hati. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```


Mengonversi paragraf yang ditentukan ke HTML dan mengembalikannya sebagai objek String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| firstParagraphIndex | int | Indeks paragraf pertama int |
| paragraphsCount | int | Jumlah paragraf int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Opsi konversi [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Mengembalikan:**
java.lang.String - HTML yang dihasilkan.