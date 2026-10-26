---
title: SoftEdge
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili efek tepi lembut.
type: docs
url: /id/com.aspose.slides/softedge/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Mewakili efek tepi lembut. Tepi bentuk menjadi kabur, sementara isi tidak terpengaruh.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getRadius()](#getRadius--) | Menentukan radius blur yang diterapkan pada tepi. |
| [setRadius(double value)](#setRadius-double-) | Menentukan radius blur yang diterapkan pada tepi. |
| [getEffective()](#getEffective--) | Mendapatkan data efek Soft Edge yang efektif dengan pewarisan yang diterapkan. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah [SoftEdge](../../com.aspose.slides/softedge) yang ditentukan sama dengan [SoftEdge](../../com.aspose.slides/softedge) saat ini. |
| [hashCode()](#hashCode--) | Berfungsi sebagai fungsi hash untuk tipe tertentu. |

### getRadius() {#getRadius--}
```
public final double getRadius()
```

Menentukan radius blur yang diterapkan pada tepi. Baca/tulis double.

**Mengembalikan:**
double

### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Menentukan radius blur yang diterapkan pada tepi. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```

Mendapatkan data efek Soft Edge yang efektif dengan pewarisan yang diterapkan.

**Mengembalikan:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - Sebuah [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Baca-saja IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

Versi. Baca-saja long.

**Mengembalikan:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Mengembalikan IPresentationComponent induk. Baca-saja [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Mengembalikan:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Menentukan apakah [SoftEdge](../../com.aspose.slides/softedge) yang ditentukan sama dengan [SoftEdge](../../com.aspose.slides/softedge) saat ini.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | [SoftEdge](../../com.aspose.slides/softedge) untuk dibandingkan. |

**Mengembalikan:**
boolean - true jika objek sama; jika tidak, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Berfungsi sebagai fungsi hash untuk tipe tertentu.

**Mengembalikan:**
int - Sebuah kode hash untuk objek saat ini.