---
title: IMasterSlideCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili koleksi master slide.
type: docs
url: /id/com.aspose.slides/imasterslidecollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

Mewakili koleksi master slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Menghapus kemunculan pertama dari objek tertentu dari koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus elemen pada indeks yang ditentukan dari koleksi. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Menghapus master slide yang tidak digunakan. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Menambahkan salinan master slide yang ditentukan ke akhir koleksi. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Menyisipkan salinan master slide yang ditentukan ke posisi tertentu dalam koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```

Mendapatkan elemen pada indeks yang ditentukan. Hanya-baca [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```

Menghapus kemunculan pertama dari objek tertentu dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide yang akan dihapus dari koleksi. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Menghapus elemen pada indeks yang ditentukan dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari elemen yang akan dihapus. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```

Menghapus master slide yang tidak digunakan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ignorePreserveField | boolean | Menentukan, apakah metode ini harus menghapus master yang tidak digunakan meskipun properti [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-)-nya disetel ke true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```

Menambahkan salinan master slide yang ditentukan ke akhir koleksi. Slide tata letak yang ditautkan juga akan disalin.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide yang akan dikloning. |

**Mengembalikan:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Slide yang ditambahkan.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Menyisipkan salinan master slide yang ditentukan ke posisi tertentu dalam koleksi. Slide tata letak yang ditautkan juga akan disalin.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks slide baru. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide yang akan dikloning. |

**Mengembalikan:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Master slide yang disisipkan.