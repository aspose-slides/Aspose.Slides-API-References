---
title: SectionCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili koleksi bagian.
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

Mewakili koleksi bagian.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Menambahkan bagian slide yang dimulai dari slide tertentu. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Menambahkan bagian kosong ke akhir koleksi. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Menambahkan bagian kosong ke posisi tertentu dalam koleksi. |
| [size()](#size--) | Mendapatkan jumlah elemen yang sebenarnya terdapat dalam koleksi. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Mengembalikan indeks dari bagian yang ditentukan dalam koleksi. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Menghapus bagian dan slide yang terdapat dalam bagian tersebut. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Menghapus bagian. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Memindahkan bagian dan slide-nya dari koleksi ke posisi yang ditentukan. |
| [clear()](#clear--) | Menghapus semua bagian dari koleksi. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin seluruh koleksi ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman untuk thread). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

Mendapatkan elemen pada indeks yang ditentukan. Hanya baca [ISection](../../com.aspose.slides/isection).

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

Menambahkan bagian kosong ke akhir koleksi.

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

Menambahkan bagian kosong ke posisi tertentu dalam koleksi.

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

Mendapatkan jumlah elemen yang sebenarnya terdapat dalam koleksi. Hanya baca int.

**Mengembalikan:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

Mengembalikan indeks dari bagian yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Bagian yang dicari. |

**Mengembalikan:**
int - Indeks bagian atau -1 jika bagian tidak berasal dari koleksi ini.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

Menghapus bagian dan slide yang terdapat dalam bagian tersebut.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Bagian yang akan dihapus dari koleksi. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

Menghapus bagian. Slide yang terdapat dalam bagian akan digabungkan ke bagian sebelumnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Bagian yang akan dihapus dari koleksi. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

Memindahkan bagian dan slide-nya dari koleksi ke posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Bagian yang akan dipindahkan. |
| index | int | Indeks target. |

### clear() {#clear--}
```
public final void clear()
```

Menghapus semua bagian dari koleksi.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Menyalin seluruh koleksi ke array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array target |
| index | int | Indeks dalam array target. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman untuk thread). Hanya baca boolean.

**Mengembalikan:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Mengembalikan akar sinkronisasi. Hanya baca Object.

**Mengembalikan:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Sebuah IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Sebuah java.util.Iterator untuk seluruh koleksi.