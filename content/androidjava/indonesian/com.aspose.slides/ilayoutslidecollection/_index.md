---
title: ILayoutSlideCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili kelas dasar untuk koleksi slide tata letak.
type: docs
url: /id/com.aspose.slides/ilayoutslidecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

Mewakili kelas dasar untuk koleksi slide tata letak.
## Metode

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan layout slide berdasarkan indeks. |
| [getByType(byte type)](#getByType-byte-) | Mengembalikan layout slide pertama dengan tipe tertentu. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Menghapus layout dari koleksi. |
| [removeUnused()](#removeUnused--) | Menghapus layout slide yang tidak terpakai (layout slide yang HasDependingSlides bernilai false). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```

Mengembalikan layout slide berdasarkan indeks. Hanya-baca [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```

Mengembalikan layout slide pertama dengan tipe tertentu.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | byte | Tipe layout slide yang akan dicari. |

**Mengembalikan:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) dengan tipe tertentu atau null jika tidak ada layout yang ditemukan.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```

Menghapus layout dari koleksi.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout slide yang akan dihapus dari koleksi.

--------------------

1) Untuk menghindari PptxEditException dilempar, periksa properti HasDependingSlides pada layout terlebih dahulu. 2) Anda juga dapat menggunakan metode [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) untuk menyederhanakan kode. |
### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```

Menghapus layout slide yang tidak terpakai (layout slide yang HasDependingSlides bernilai false).