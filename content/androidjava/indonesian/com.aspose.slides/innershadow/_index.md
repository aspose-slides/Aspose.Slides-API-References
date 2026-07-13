---
title: InnerShadow
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili efek Inner Shadow.
type: docs
url: /id/com.aspose.slides/innershadow/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IInnerShadow](../../com.aspose.slides/iinnershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class InnerShadow implements IInnerShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Mewakili efek Inner Shadow.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Radius blur. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Radius blur. |
| [getDirection()](#getDirection--) | Arah bayangan. |
| [setDirection(float value)](#setDirection-float-) | Arah bayangan. |
| [getDistance()](#getDistance--) | Jarak bayangan. |
| [setDistance(double value)](#setDistance-double-) | Jarak bayangan. |
| [getShadowColor()](#getShadowColor--) | Warna bayangan. |
| [getEffective()](#getEffective--) | Mendapatkan data efek Inner Shadow yang efektif dengan pewarisan yang diterapkan. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah [InnerShadow](../../com.aspose.slides/innershadow) yang ditentukan sama dengan [InnerShadow](../../com.aspose.slides/innershadow) saat ini. |
| [hashCode()](#hashCode--) | Berfungsi sebagai fungsi hash untuk tipe tertentu. |
### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

Radius blur. Baca/tulis double.

**Mengembalikan:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

Radius blur. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

Arah bayangan. Baca/tulis float.

**Mengembalikan:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

Arah bayangan. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

Jarak bayangan. Baca/tulis double.

**Mengembalikan:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

Jarak bayangan. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

Warna bayangan. Hanya-baca [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IInnerShadowEffectiveData getEffective()
```

Mendapatkan data efek Inner Shadow yang efektif dengan pewarisan yang diterapkan.

**Mengembalikan:**
[IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata) - A [IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Hanya-baca IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Versi. Hanya-baca long.

**Mengembalikan:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Mengembalikan IPresentationComponent induk. Hanya-baca [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Mengembalikan:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Menentukan apakah [InnerShadow](../../com.aspose.slides/innershadow) yang ditentukan sama dengan [InnerShadow](../../com.aspose.slides/innershadow) saat ini.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | [InnerShadow](../../com.aspose.slides/innershadow) untuk dibandingkan. |

**Mengembalikan:**
boolean - true jika objek sama; lainnya false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Berfungsi sebagai fungsi hash untuk tipe tertentu.

**Mengembalikan:**
int - Kode hash untuk objek saat ini.