---
title: MasterSlideCollection
second_title: Aspose.Slides untuk Referensi API Java
description: Mewakili kumpulan slide master.
type: docs
url: /id/com.aspose.slides/masterslidecollection/
---
**Warisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

Mewakili kumpulan slide master.
## Metode

| Method | Description |
| --- | --- |
| [size()](#size--) | Mengambil jumlah elemen yang sebenarnya terkandung dalam kumpulan. |
| [get_Item(int index)](#get-Item-int-) | Mengambil elemen pada indeks yang ditentukan. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Menghapus kemunculan pertama dari objek tertentu dari kumpulan. |
| [removeAt(int index)](#removeAt-int-) | Menghapus elemen pada indeks yang ditentukan dalam kumpulan. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Menghapus slide master yang tidak terpakai. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Menambahkan salinan slide master tertentu ke akhir kumpulan. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Menyisipkan salinan slide master tertentu ke posisi yang ditentukan dalam kumpulan. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin semua elemen dari kumpulan ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke kumpulan disinkronkan (aman terhadap thread). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi kumpulan. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh kumpulan. |
### size() {#size--}
```
public final int size()
```

Mengambil jumlah elemen yang sebenarnya terkandung dalam kumpulan. Hanya-baca int.

**Mengembalikan:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```

Mengambil elemen pada indeks yang ditentukan. Hanya-baca [MasterSlide](../../com.aspose.slides/masterslide).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```

Menghapus kemunculan pertama dari objek tertentu dari kumpulan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide master yang akan dihapus dari kumpulan. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Menghapus elemen pada indeks yang ditentukan dalam kumpulan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari elemen yang akan dihapus.

--------------------

Untuk menghindari terlemparnya PptxEditException, periksa properti HasDependingSlides milik master terlebih dahulu. |
### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

Menghapus slide master yang tidak terpakai.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ignorePreserveField | boolean | Menentukan apakah metode ini harus menghapus master yang tidak terpakai bahkan jika properti [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-)-nya diset ke true. |
### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```

Menambahkan salinan slide master tertentu ke akhir kumpulan. Slide tata letak yang terhubung juga akan disalin.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide yang akan diklon. |

**Mengembalikan:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Slide yang ditambahkan.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Menyisipkan salinan slide master tertentu ke posisi yang ditentukan dalam kumpulan. Slide tata letak yang terhubung juga akan disalin.

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
>          // Slide master
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // Mendapatkan Slide Master dari presentasi tujuan
>          IMasterSlideCollection masters = destPres.getMasters();
>          // Mengkloning slide master yang diinginkan dari presentasi sumber ke koleksi master dalam
>          // Presentasi tujuan
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // Koleksi slide dalam presentasi tujuan
>          ISlideCollection slds = destPres.getSlides();
>          // Mengkloning slide sumber ke koleksi slide tujuan.
>          slds.addClone(SourceSlide, iSlide, true);
>          // Menyimpan presentasi tujuan ke disk
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks slide baru. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide yang akan diklon. |

**Mengembalikan:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Slide master yang disisipkan.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Menyalin semua elemen dari kumpulan ke array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array target. |
| index | int | Indeks mulai dalam array target. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Mengembalikan nilai yang menunjukkan apakah akses ke kumpulan disinkronkan (aman terhadap thread). Hanya-baca boolean.

**Mengembalikan:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Mengembalikan akar sinkronisasi. Hanya-baca Object.

**Mengembalikan:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

Mengembalikan enumerator yang mengiterasi kumpulan.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Sebuah IGenericEnumerator yang dapat digunakan untuk mengiterasi kumpulan.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

Mengembalikan iterator java untuk seluruh kumpulan.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Sebuah java.util.Iterator untuk seluruh kumpulan.