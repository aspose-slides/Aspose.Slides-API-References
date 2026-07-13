---
title: ISectionCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili koleksi bagian.
type: docs
url: /id/com.aspose.slides/isectioncollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

Mewakili koleksi seksi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Menambahkan bagian baru yang dimulai dari slide tertentu. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Menambahkan bagian kosong ke posisi yang ditentukan dalam koleksi. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Menghapus bagian dan slide yang terdapat dalam bagian tersebut. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Menghapus bagian. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Memindahkan bagian dan slide-nya dari koleksi ke posisi yang ditentukan. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Menambahkan bagian kosong ke akhir koleksi. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Mengembalikan indeks bagian yang ditentukan dalam koleksi. |
| [clear()](#clear--) | Menghapus semua bagian dari koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
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
public abstract ISection addSection(String name, ISlide startedFromSlide)
```

Menambahkan bagian baru yang dimulai dari slide tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama bagian |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Slide pertama bagian |

**Mengembalikan:**
[ISection](../../com.aspose.slides/isection) - Bagian yang ditambahkan.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```

Menambahkan bagian kosong ke posisi yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama bagian |
| index | int | Indeks bagian baru. |

**Mengembalikan:**
[ISection](../../com.aspose.slides/isection) - Bagian yang ditambahkan.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```

Menghapus bagian dan slide yang terdapat dalam bagian tersebut.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Bagian yang akan dihapus dari koleksi. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```

Menghapus bagian. Slide yang terdapat dalam bagian akan digabungkan ke bagian sebelumnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Bagian yang akan dihapus dari koleksi. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```

Memindahkan bagian dan slide-nya dari koleksi ke posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Bagian yang akan dipindahkan. |
| index | int | Indeks tujuan. |

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```

Menambahkan bagian kosong ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama bagian |

**Mengembalikan:**
[ISection](../../com.aspose.slides/isection) - Bagian yang ditambahkan.
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```

Mengembalikan indeks bagian yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Bagian yang dicari. |

**Mengembalikan:**
int - Indeks sebuah bagian atau -1 jika bagian tidak berasal dari koleksi ini.
### clear() {#clear--}
```
public abstract void clear()
```

Menghapus semua bagian dari koleksi.