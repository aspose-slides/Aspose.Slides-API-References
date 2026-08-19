---
title: LayoutSlideCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili kelas dasar untuk koleksi layout slide.
type: docs
url: /id/com.aspose.slides/layoutslidecollection/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

Mewakili kelas dasar untuk koleksi layout slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [size()](#size--) | Mengembalikan jumlah layout slide dalam koleksi. |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan layout slide berdasarkan indeks. |
| [getByType(byte type)](#getByType-byte-) | Mengembalikan layout slide pertama dengan tipe yang ditentukan. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Menghapus layout dari koleksi. |
| [removeUnused()](#removeUnused--) | Menghapus layout slide yang tidak terpakai (layout slide yang HasDependingSlides bernilai false). |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin semua elemen dari koleksi ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

Mengembalikan jumlah layout slide dalam koleksi. Hanya-baca int.

**Mengembalikan:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```

Mengembalikan layout slide berdasarkan indeks. Hanya-baca [LayoutSlide](../../com.aspose.slides/layoutslide).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```

Mengembalikan layout slide pertama dengan tipe yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | byte | Tipe layout slide yang akan dicari. |

**Mengembalikan:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) dengan tipe yang ditentukan atau null jika tidak ada layout yang ditemukan.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```

Menghapus layout dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout slide yang akan dihapus dari koleksi.

--------------------

1) Untuk menghindari lemparan PptxEditException, periksa properti HasDependingSlides layout terlebih dahulu. 2) Anda juga dapat menggunakan metode [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) untuk menyederhanakan kode. |
### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```

Menghapus layout slide yang tidak terpakai (layout slide yang HasDependingSlides bernilai false).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - Sebuah IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - Sebuah java.util.Iterator untuk seluruh koleksi.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Menyalin semua elemen dari koleksi ke array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array target. |
| index | int | Indeks mulai pada array target. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (thread-safe). Hanya-baca boolean.

**Mengembalikan:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Mengembalikan akar sinkronisasi. Hanya-baca Object.

**Mengembalikan:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Hanya-baca IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject