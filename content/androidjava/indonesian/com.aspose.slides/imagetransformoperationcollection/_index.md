---
title: ImageTransformOperationCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili kumpulan efek yang diterapkan pada sebuah gambar.
type: docs
url: /id/com.aspose.slides/imagetransformoperationcollection/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

Mewakili kumpulan efek yang diterapkan pada sebuah gambar.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan sebuah [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) dari koleksi berdasarkan indeksnya. |
| [removeAt(int index)](#removeAt-int-) | Menghapus efek gambar dari koleksi pada indeks yang ditentukan. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Menambahkan efek Alpha Bi-Level baru ke akhir koleksi. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Menambahkan efek Alpha Ceiling baru ke akhir koleksi. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Menambahkan efek Alpha Floor baru ke akhir koleksi. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Menambahkan efek Alpha Inverse baru ke akhir koleksi. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Menambahkan efek Alpha Modulate baru ke akhir koleksi. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Menambahkan efek Alpha Modulate Fixed baru ke akhir koleksi. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Menambahkan efek Alpha Replace baru ke akhir koleksi. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Menambahkan efek Bi-Level (hitam/putih) baru ke akhir koleksi. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Menambahkan efek Blur baru ke akhir koleksi. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Menambahkan efek Color Change baru ke akhir koleksi. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Menambahkan efek Color Replacement baru ke akhir koleksi. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Menambahkan efek Duotone baru ke akhir koleksi. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Menambahkan efek Fill Overlay baru ke akhir koleksi. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Menambahkan efek Gray Scale baru ke akhir koleksi. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Menambahkan efek Hue/Saturation/Luminance baru ke akhir koleksi. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Menambahkan efek Luminance baru ke akhir koleksi. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Menambahkan efek Tint baru ke akhir koleksi. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Menambahkan efek BrightnessContrast baru ke akhir koleksi. |
| [size()](#size--) | Mengembalikan jumlah efek gambar dalam sebuah koleksi. |
| [isReadOnly()](#isReadOnly--) | Mendapatkan nilai yang menunjukkan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) bersifat read-only. |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | Menambahkan efek gambar baru ke akhir koleksi. |
| [clear()](#clear--) | Menghapus semua efek gambar dari sebuah koleksi. |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | Menentukan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) berisi nilai tertentu. |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | Menyalin elemen [IGenericCollection](../../com.aspose.slides/igenericcollection) ke sebuah Array, mulai pada indeks Array tertentu. |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | Menghapus kemunculan pertama dari objek tertentu dari [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versi. Read-only long.

**Mengembalikan:**
long
### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

Mengembalikan sebuah [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) dari koleksi berdasarkan indeksnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks elemen. |

**Mengembalikan:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - Objek [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Menghapus efek gambar dari koleksi pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks efek gambar yang harus dihapus. |
### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Menambahkan efek Alpha Bi-Level baru ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threshold | float | Nilai ambang untuk efek alpha bi-level. |

**Mengembalikan:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Indeks efek gambar baru dalam koleksi.
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

Menambahkan efek Alpha Ceiling baru ke akhir koleksi.

**Mengembalikan:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Indeks efek gambar baru dalam koleksi.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

Menambahkan efek Alpha Floor baru ke akhir koleksi.

**Mengembalikan:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Indeks efek gambar baru dalam koleksi.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

Menambahkan efek Alpha Inverse baru ke akhir koleksi.

**Mengembalikan:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Indeks efek gambar baru dalam koleksi.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

Menambahkan efek Alpha Modulate baru ke akhir koleksi.

**Mengembalikan:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Indeks efek gambar baru dalam koleksi.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Menambahkan efek Alpha Modulate Fixed baru ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| amount | float | Persentase untuk menskalakan alpha. |

**Mengembalikan:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Indeks efek gambar baru dalam koleksi.
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Menambahkan efek Alpha Replace baru ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alpha | float | Nilai opasitas baru. |

**Mengembalikan:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Indeks efek gambar baru dalam koleksi.
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

Menambahkan efek Bi-Level (hitam/putih) baru ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threshold | float | Ambang luminansi untuk efek Bi-Level. Nilai yang lebih besar atau sama dengan ambang diatur menjadi putih. Nilai yang lebih kecil dari ambang diatur menjadi hitam. |

**Mengembalikan:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Indeks efek gambar baru dalam koleksi.
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

Menambahkan efek Blur baru ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| radius | double | Radius blur. |
| grow | boolean | Menentukan apakah batas objek harus diperluas akibat blur. True berarti batas diperluas, false berarti tidak. |

**Mengembalikan:**
[IBlur](../../com.aspose.slides/iblur) - Indeks efek gambar baru dalam koleksi.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

Menambahkan efek Color Change baru ke akhir koleksi.

**Mengembalikan:**
[IColorChange](../../com.aspose.slides/icolorchange) - Indeks efek gambar baru dalam koleksi.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

Menambahkan efek Color Replacement baru ke akhir koleksi.

**Mengembalikan:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Indeks efek gambar baru dalam koleksi.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

Menambahkan efek Duotone baru ke akhir koleksi.

**Mengembalikan:**
[IDuotone](../../com.aspose.slides/iduotone) - Indeks efek gambar baru dalam koleksi.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

Menambahkan efek Fill Overlay baru ke akhir koleksi.

**Mengembalikan:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Indeks efek gambar baru dalam koleksi.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

Menambahkan efek Gray Scale baru ke akhir koleksi.

**Mengembalikan:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Indeks efek gambar baru dalam koleksi.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Menambahkan efek Hue/Saturation/Luminance baru ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hue | float | Jumlah derajat penyesuaian hue. |
| saturation | float | Persentase penyesuaian saturasi. |
| luminance | float | Persentase penyesuaian luminansi. |

**Mengembalikan:**
[IHSL](../../com.aspose.slides/ihsl) - Indeks efek gambar baru dalam koleksi.
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

Menambahkan efek Luminance baru ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brightness | float | Persen perubahan kecerahan. |
| contrast | float | Persen perubahan kontras. |

**Mengembalikan:**
[ILuminance](../../com.aspose.slides/iluminance) - Indeks efek gambar baru dalam koleksi.
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

Menambahkan efek Tint baru ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hue | float | Hue yang menjadi arah tint. |
| amount | float | Menentukan seberapa banyak nilai warna digeser. |

**Mengembalikan:**
[ITint](../../com.aspose.slides/itint) - Indeks efek gambar baru dalam koleksi.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Menambahkan efek BrightnessContrast baru ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brightness | float | Persen perubahan kecerahan. |
| contrast | float | Persen perubahan kontras. |

**Mengembalikan:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Indeks efek gambar baru dalam koleksi.
### size() {#size--}
```
public final int size()
```

Mengembalikan jumlah efek gambar dalam koleksi. Read-only int .

**Mengembalikan:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Mendapatkan nilai yang menunjukkan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) bersifat read-only. Read-only boolean.

**Mengembalikan:**
boolean - true jika [IGenericCollection](../../com.aspose.slides/igenericcollection) bersifat read-only; jika tidak, false.
### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

Menambahkan efek gambar baru ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Efek gambar yang akan ditambahkan ke akhir koleksi. |
### clear() {#clear--}
```
public final void clear()
```

Menghapus semua efek gambar dari koleksi.
### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```

Menentukan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) berisi nilai tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Objek yang akan dicari dalam [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Mengembalikan:**
boolean - true jika item ditemukan dalam [IGenericCollection](../../com.aspose.slides/igenericcollection); jika tidak, false.
### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

Menyalin elemen [IGenericCollection](../../com.aspose.slides/igenericcollection) ke sebuah Array, mulai pada indeks Array tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | Array satu dimensi yang menjadi tujuan elemen yang disalin dari [IGenericCollection](../../com.aspose.slides/igenericcollection). Array harus memiliki indeks berbasis nol. |
| arrayIndex | int | Indeks berbasis nol dalam array dimana penyalinan dimulai. |
### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

Menghapus kemunculan pertama dari objek tertentu dari [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Objek yang akan dihapus dari [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Mengembalikan:**
boolean - true jika item berhasil dihapus dari [IGenericCollection](../../com.aspose.slides/igenericcollection); jika tidak, false. Metode ini juga mengembalikan false jika item tidak ditemukan dalam [IGenericCollection](../../com.aspose.slides/igenericcollection) yang asli.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - java.util.Iterator untuk seluruh koleksi.