---
title: FillOverlay
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili efek Fill Overlay.
type: docs
url: /id/com.aspose.slides/filloverlay/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

Mewakili efek Fill Overlay. Fill overlay dapat digunakan untuk menentukan isian tambahan untuk sebuah objek dan menggabungkan kedua isian tersebut.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Format isian. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | Mendapatkan data efek Fill Overlay yang efektif dengan pewarisan yang diterapkan. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah [FillOverlay](../../com.aspose.slides/filloverlay) yang ditentukan sama dengan [FillOverlay](../../com.aspose.slides/filloverlay) saat ini. |
| [hashCode()](#hashCode--) | Berfungsi sebagai fungsi hash untuk tipe tertentu. |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Format isian. Baca-saja [IFillFormat](../../com.aspose.slides/ifillformat).

**Mengembalikan:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBlend() {#getBlend--}
```
public final int getBlend()
```

FillBlendMode. Baca/tulis [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Mengembalikan:**
int
### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```

FillBlendMode. Baca/tulis [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```

Mendapatkan data efek Fill Overlay yang efektif dengan pewarisan yang diterapkan.

**Mengembalikan:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - Sebuah [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versi. Baca-saja long.

**Mengembalikan:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Menentukan apakah [FillOverlay](../../com.aspose.slides/filloverlay) yang ditentukan sama dengan [FillOverlay](../../com.aspose.slides/filloverlay) saat ini.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | [FillOverlay](../../com.aspose.slides/filloverlay) untuk dibandingkan. |

**Mengembalikan:**
boolean - true jika objek sama; lainnya, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Berfungsi sebagai fungsi hash untuk tipe tertentu.

**Mengembalikan:**
int - Kode hash untuk objek saat ini.