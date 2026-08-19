---
title: SectionCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili kumpulan bagian.
type: docs
url: /id/com.aspose.slides/sectioncollection/
---
**Pewarisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

Represents a collection of sections.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Menambahkan bagian slide yang dimulai dari slide tertentu. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Menambahkan bagian kosong ke akhir kumpulan. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Menambahkan bagian kosong ke posisi tertentu dalam kumpulan. |
| [size()](#size--) | Mendapatkan jumlah elemen yang sebenarnya terkandung dalam kumpulan. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Mengembalikan indeks dari bagian yang ditentukan dalam kumpulan. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Menghapus bagian dan slide yang terdapat dalam bagian tersebut. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Menghapus bagian. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Memindahkan bagian dan slide-nya dari kumpulan ke posisi yang ditentukan. |
| [clear()](#clear--) | Menghapus semua bagian dari kumpulan. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin seluruh kumpulan ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke kumpulan disinkronkan (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi kumpulan. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh kumpulan. |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

Mendapatkan elemen pada indeks yang ditentukan. Baca-saja [ISection](../../com.aspose.slides/isection).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```

Menambahkan bagian slide yang dimulai dari slide tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama bagian |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Slide pertama dari bagian |

**Mengembalikan:**
[ISection](../../com.aspose.slides/isection) - Bagian yang ditambahkan.
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```

Menambahkan bagian kosong ke akhir kumpulan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama bagian |

**Mengembalikan:**
[ISection](../../com.aspose.slides/isection) - Bagian yang ditambahkan.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```

Menambahkan bagian kosong ke posisi tertentu dalam kumpulan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama bagian |
| index | int | Indeks bagian baru. |

**Mengembalikan:**
[ISection](../../com.aspose.slides/isection) - Bagian yang ditambahkan.
### size() {#size--}
```
public final int size()
```

Mendapatkan jumlah elemen yang sebenarnya terkandung dalam kumpulan. Baca-saja int.

**Mengembalikan:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

Mengembalikan indeks dari bagian yang ditentukan dalam kumpulan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Bagian yang dicari. |

**Mengembalikan:**
int - Indeks bagian atau -1 jika bagian tidak berasal dari kumpulan ini.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

Menghapus bagian dan slide yang terdapat dalam bagian.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Bagian yang akan dihapus dari kumpulan. |
### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

Menghapus bagian. Slide yang terdapat dalam bagian akan digabungkan ke bagian sebelumnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Bagian yang akan dihapus dari kumpulan. |
### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

Memindahkan bagian dan slide-nya dari kumpulan ke posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Bagian yang akan dipindahkan. |
| index | int | Indeks target. |
### clear() {#clear--}
```
public final void clear()
```

Menghapus semua bagian dari kumpulan.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Menyalin seluruh kumpulan ke array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array target |
| index | int | Indeks dalam array target. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Mengembalikan nilai yang menunjukkan apakah akses ke kumpulan disinkronkan (thread-safe). Baca-saja boolean.

**Mengembalikan:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Mengembalikan akar sinkronisasi. Baca-saja Object.

**Mengembalikan:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

Mengembalikan enumerator yang mengiterasi kumpulan.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

Mengembalikan iterator java untuk seluruh kumpulan.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - An java.util.Iterator for the entire collection.