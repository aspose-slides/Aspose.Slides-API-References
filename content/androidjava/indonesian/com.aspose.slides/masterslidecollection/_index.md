---
title: MasterSlideCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili koleksi master slide.
type: docs
url: /id/com.aspose.slides/masterslidecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

Mewakili koleksi master slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [size()](#size--) | Mendapatkan jumlah elemen yang benar-benar terdapat dalam koleksi. |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Menghapus kemunculan pertama objek tertentu dari koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus elemen pada indeks yang ditentukan dalam koleksi. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Menghapus master slide yang tidak terpakai. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Menambahkan salinan master slide tertentu ke akhir koleksi. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Menyisipkan salinan master slide tertentu ke posisi yang ditentukan dalam koleksi. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin semua elemen dari koleksi ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman untuk thread). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
### size() {#size--}
```
public final int size()
```


Mendapatkan jumlah elemen yang benar-benar terdapat dalam koleksi. int hanya-baca.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```


Mendapatkan elemen pada indeks yang ditentukan. [MasterSlide](../../com.aspose.slides/masterslide) hanya-baca.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```


Menghapus kemunculan pertama objek tertentu dari koleksi.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide yang akan dihapus dari koleksi. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Menghapus elemen pada indeks yang ditentukan dalam koleksi.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari elemen yang akan dihapus.

--------------------

Untuk menghindari terlemparnya PptxEditException, periksa properti HasDependingSlides master terlebih dahulu. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```


Menghapus master slide yang tidak terpakai.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ignorePreserveField | boolean | Menentukan apakah metode ini harus menghapus master yang tidak terpakai meskipun properti [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-)-nya bernilai true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```


Menambahkan salinan master slide tertentu ke akhir koleksi. Slide tata letak yang terhubung juga akan disalin.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide yang akan diklon. |

**Returns:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Slide yang ditambahkan.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```


Menyisipkan salinan master slide tertentu ke posisi yang ditentukan dalam koleksi. Slide tata letak yang terhubung juga akan disalin.

--------------------

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // Membuat instance kelas Presentation untuk memuat file presentasi sumber
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // Membuat instance kelas Presentation untuk presentasi tujuan (tempat slide akan diklon)
>      Presentation destPres = new Presentation();
>      try {
>          // Membuat instance ISlide dari koleksi slide dalam presentasi sumber bersama dengan
>          // master slide
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // Dapatkan Master Slide dari presentasi tujuan
>          IMasterSlideCollection masters = destPres.getMasters();
>          // Klon master slide yang diinginkan dari presentasi sumber ke dalam koleksi master di
>          // presentasi tujuan
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // Koleksi slide dalam presentasi tujuan
>          ISlideCollection slds = destPres.getSlides();
>          // Klon slide sumber ke koleksi slide tujuan.
>          slds.addClone(SourceSlide, iSlide, true);
>          // Simpan presentasi tujuan ke disk
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks slide baru. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide yang akan diklon. |

**Returns:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Master slide yang disisipkan.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Menyalin semua elemen dari koleksi ke array yang ditentukan.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array target. |
| index | int | Indeks mulai dalam array target. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman untuk thread). boolean hanya-baca.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Mengembalikan akar sinkronisasi. Object hanya-baca.

**Returns:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```


Mengembalikan enumerator yang mengiterasi koleksi.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```


Mengembalikan iterator java untuk seluruh koleksi.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - java.util.Iterator untuk seluruh koleksi.