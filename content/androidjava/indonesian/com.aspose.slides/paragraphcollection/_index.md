---
title: ParagraphCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili koleksi paragraf.
type: docs
url: /id/com.aspose.slides/paragraphcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

Mewakili koleksi paragraf.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCount()](#getCount--) | Mendapatkan jumlah elemen yang sebenarnya terdapat dalam koleksi. |
| [isReadOnly()](#isReadOnly--) | Mendapatkan nilai yang menunjukkan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) bersifat hanya-baca. |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Menambahkan Paragraph ke akhir koleksi. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Menambahkan isi ParagraphCollection ke akhir koleksi. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | Menentukan indeks dari item tertentu dalam List. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Menyisipkan Paragraph ke dalam koleksi pada indeks yang ditentukan. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Menyisipkan isi ParagraphCollection ke dalam koleksi pada indeks yang ditentukan. |
| [clear()](#clear--) | Menghapus semua elemen dari koleksi. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | Menentukan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) berisi nilai tertentu. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | Menyalin elemen [IGenericCollection](../../com.aspose.slides/igenericcollection) ke sebuah Array, dimulai pada indeks Array tertentu. |
| [removeAt(int index)](#removeAt-int-) | Menghapus elemen pada indeks yang ditentukan dalam koleksi. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Menghapus kemunculan pertama dari objek tertentu dari [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [getSlide()](#getSlide--) | Mengembalikan slide induk dari koleksi paragraf. |
| [getPresentation()](#getPresentation--) | Mengembalikan presentasi induk dari koleksi paragraf. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Menambahkan teks dari string html yang ditentukan ke koleksi. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Menambahkan teks dari string html yang ditentukan ke koleksi. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Mengonversi paragraf yang ditentukan ke HTML dan mengembalikannya sebagai objek String. |
### getCount() {#getCount--}
```
public final int getCount()
```


Mendapatkan jumlah elemen yang sebenarnya terdapat dalam koleksi. Hanya-baca int.

**Mengembalikan:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Mendapatkan nilai yang menunjukkan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) bersifat hanya-baca. Hanya-baca boolean.

**Mengembalikan:**
boolean - true jika [IGenericCollection](../../com.aspose.slides/igenericcollection) bersifat hanya-baca; sebaliknya, false.
### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```


Mendapatkan elemen pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IParagraph](../../com.aspose.slides/iparagraph)
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```


Menambahkan Paragraph ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph yang akan ditambahkan ke akhir koleksi. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```


Menambahkan isi ParagraphCollection ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | ParagraphCollection yang akan ditambahkan ke akhir koleksi. |

**Mengembalikan:**
int - Indeks di mana Paragraph ditambahkan atau -1 jika tidak ada yang dapat ditambahkan.
### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```


Menentukan indeks dari item tertentu dalam List.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Objek yang akan dicari dalam List. |

**Mengembalikan:**
int - Indeks item jika ditemukan dalam list; sebaliknya, -1.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```


Menyisipkan Paragraph ke dalam koleksi pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat Paragraph harus disisipkan. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph yang akan disisipkan. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```


Menyisipkan isi ParagraphCollection ke dalam koleksi pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat paragraf harus disisipkan. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Paragraf yang akan disisipkan. |

### clear() {#clear--}
```
public final void clear()
```


Menghapus semua elemen dari koleksi.

### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```


Menentukan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) berisi nilai tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Objek yang akan dicari dalam [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Mengembalikan:**
boolean - true jika item ditemukan dalam [IGenericCollection](../../com.aspose.slides/igenericcollection); sebaliknya, false.
### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```


Menyalin elemen [IGenericCollection](../../com.aspose.slides/igenericcollection) ke sebuah Array, dimulai pada indeks Array tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | Array satu dimensi yang menjadi tujuan elemen yang disalin dari [IGenericCollection](../../com.aspose.slides/igenericcollection). Array harus memiliki indeks berbasis nol. |
| arrayIndex | int | Indeks berbasis nol dalam array tempat penyalinan dimulai. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Menghapus elemen pada indeks yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol elemen yang akan dihapus. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```


Menghapus kemunculan pertama dari objek tertentu dari [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Objek yang akan dihapus dari [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Mengembalikan:**
boolean - true jika item berhasil dihapus dari [IGenericCollection](../../com.aspose.slides/igenericcollection); sebaliknya, false. Metode ini juga mengembalikan false jika item tidak ditemukan dalam [IGenericCollection](../../com.aspose.slides/igenericcollection) asli.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```


Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - Sebuah IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```


Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - Sebuah java.util.Iterator untuk seluruh koleksi.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Mengembalikan slide induk dari koleksi paragraf. Hanya-baca [BaseSlide](../../com.aspose.slides/baseslide).

**Mengembalikan:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Mengembalikan presentasi induk dari koleksi paragraf. Hanya-baca [IPresentation](../../com.aspose.slides/ipresentation).

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation)
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```


Menambahkan teks dari string html yang ditentukan ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
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
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
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