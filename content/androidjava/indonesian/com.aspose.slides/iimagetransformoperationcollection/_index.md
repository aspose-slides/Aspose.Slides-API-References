---
title: IImageTransformOperationCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili kumpulan efek yang diterapkan pada sebuah gambar.
type: docs
url: /id/com.aspose.slides/iimagetransformoperationcollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

Mewakili kumpulan efek yang diterapkan pada sebuah gambar.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan sebuah [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) dari koleksi berdasarkan indeksnya. |
| [removeAt(int index)](#removeAt-int-) | Menghapus sebuah efek gambar dari koleksi pada indeks yang ditentukan. |
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
### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

Mengembalikan sebuah [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) dari koleksi berdasarkan indeksnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks dari item. |

**Mengembalikan:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - Objek [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Menghapus efek gambar dari koleksi pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks efek gambar yang harus dihapus. |
### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
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
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

Menambahkan efek Alpha Ceiling baru ke akhir koleksi.

**Mengembalikan:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Indeks efek gambar baru dalam koleksi.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

Menambahkan efek Alpha Floor baru ke akhir koleksi.

**Mengembalikan:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Indeks efek gambar baru dalam koleksi.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

Menambahkan efek Alpha Inverse baru ke akhir koleksi.

**Mengembalikan:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Indeks efek gambar baru dalam koleksi.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

Menambahkan efek Alpha Modulate baru ke akhir koleksi.

**Mengembalikan:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Indeks efek gambar baru dalam koleksi.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Menambahkan efek Alpha Modulate Fixed baru ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| amount | float | Persentase untuk mengubah skala alpha. |

**Mengembalikan:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Indeks efek gambar baru dalam koleksi.
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
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
public abstract IBiLevel addBiLevelEffect(float threshold)
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
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

Menambahkan efek Blur baru ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| radius | double | Radius blur. |
| grow | boolean | Menentukan apakah batas objek harus diperluas sebagai akibat blur. True menunjukkan batas diperluas, sementara false menunjukkan tidak. |

**Mengembalikan:**
[IBlur](../../com.aspose.slides/iblur) - Indeks efek gambar baru dalam koleksi.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

Menambahkan efek Color Change baru ke akhir koleksi.

**Mengembalikan:**
[IColorChange](../../com.aspose.slides/icolorchange) - Indeks efek gambar baru dalam koleksi.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

Menambahkan efek Color Replacement baru ke akhir koleksi.

**Mengembalikan:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Indeks efek gambar baru dalam koleksi.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

Menambahkan efek Duotone baru ke akhir koleksi.

**Mengembalikan:**
[IDuotone](../../com.aspose.slides/iduotone) - Indeks efek gambar baru dalam koleksi.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

Menambahkan efek Fill Overlay baru ke akhir koleksi.

**Mengembalikan:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Indeks efek gambar baru dalam koleksi.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

Menambahkan efek Gray Scale baru ke akhir koleksi.

**Mengembalikan:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Indeks efek gambar baru dalam koleksi.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Menambahkan efek Hue/Saturation/Luminance baru ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hue | float | Jumlah derajat untuk mengubah hue. |
| saturation | float | Persentase penyesuaian saturasi. |
| luminance | float | Persentase penyesuaian luminansi. |

**Mengembalikan:**
[IHSL](../../com.aspose.slides/ihsl) - Indeks efek gambar baru dalam koleksi.
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
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
public abstract ITint addTintEffect(float hue, float amount)
```

Menambahkan efek Tint baru ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hue | float | Hue yang akan ditint. |
| amount | float | Menentukan seberapa banyak nilai warna digeser. |

**Mengembalikan:**
[ITint](../../com.aspose.slides/itint) - Indeks efek gambar baru dalam koleksi.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Menambahkan efek BrightnessContrast baru ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brightness | float | Persen perubahan kecerahan. |
| contrast | float | Persen perubahan kontras. |

**Mengembalikan:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Indeks efek gambar baru dalam koleksi.