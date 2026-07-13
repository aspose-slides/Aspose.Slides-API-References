---
title: LayoutSlideCollection
second_title: Referensi API Java untuk Aspose.Slides untuk Android
description: Mewakili kelas dasar untuk koleksi slide tata letak.
type: docs
url: /id/com.aspose.slides/layoutslidecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

Mewakili kelas dasar untuk koleksi slide tata letak.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [size()](#size--) | Mengembalikan jumlah slide tata letak dalam koleksi. |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan slide tata letak berdasarkan indeks. |
| [getByType(byte type)](#getByType-byte-) | Mengembalikan slide tata letak pertama dengan tipe tertentu. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Menghapus tata letak dari koleksi. |
| [removeUnused()](#removeUnused--) | Menghapus slide tata letak yang tidak terpakai (slide tata letak yang HasDependingSlides-nya false). |
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

Mengembalikan jumlah slide tata letak dalam koleksi. int Baca-saja.

**Mengembalikan:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```

Mengembalikan slide tata letak berdasarkan indeks. [LayoutSlide](../../com.aspose.slides/layoutslide) Baca-saja.

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

Mengembalikan slide tata letak pertama dengan tipe tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | byte | Tipe slide tata letak yang akan dicari. |

**Mengembalikan:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) dengan tipe yang ditentukan atau null jika tidak ada tata letak yang ditemukan.

### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```

Menghapus tata letak dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide tata letak yang akan dihapus dari koleksi.

--------------------
1) Untuk menghindari lemparan PptxEditException, periksa properti HasDependingSlides tata letak terlebih dahulu. 2) Anda juga dapat menggunakan metode [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) untuk menyederhanakan kode. |

### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```

Menghapus slide tata letak yang tidak terpakai (slide tata letak yang HasDependingSlides-nya false).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - An java.util.Iterator for the entire collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Menyalin semua elemen dari koleksi ke array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array target. |
| index | int | Indeks mulai dalam array target. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (thread-safe). boolean Baca-saja.

**Mengembalikan:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Mengembalikan akar sinkronisasi. Object Baca-saja.

**Mengembalikan:**
java.lang.Object

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. IDOMObject Baca-saja.

**Mengembalikan:**
com.aspose.slides.IDOMObject