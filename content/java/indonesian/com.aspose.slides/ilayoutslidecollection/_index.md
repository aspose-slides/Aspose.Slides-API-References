---
title: ILayoutSlideCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili kelas dasar untuk koleksi slide tata letak.
type: docs
url: /id/com.aspose.slides/ilayoutslidecollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

Mewakili kelas dasar untuk koleksi slide tata letak.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan slide tata letak berdasarkan indeks. |
| [getByType(byte type)](#getByType-byte-) | Mengembalikan slide tata letak pertama dengan tipe yang ditentukan. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Menghapus tata letak dari koleksi. |
| [removeUnused()](#removeUnused--) | Menghapus slide tata letak yang tidak digunakan (slide tata letak yang HasDependingSlides bernilai false). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```


Mengembalikan slide tata letak berdasarkan indeks. Hanya-baca [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```


Mengembalikan slide tata letak pertama dengan tipe yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | byte | Tipe slide tata letak yang akan dicari. |

**Mengembalikan:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) dengan tipe yang ditentukan atau null jika tidak ada tata letak yang ditemukan.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```


Menghapus tata letak dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide tata letak yang akan dihapus dari koleksi.

--------------------

1) Untuk menghindari melempar PptxEditException, periksa properti HasDependingSlides pada tata letak terlebih dahulu. 2) Anda juga dapat menggunakan metode [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) untuk menyederhanakan kode. |
### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```


Menghapus slide tata letak yang tidak digunakan (slide tata letak yang HasDependingSlides bernilai false).