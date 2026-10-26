---
title: Glow
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili efek Glow di mana outline berwarna yang kabur ditambahkan di luar tepi objek.
type: docs
url: /id/com.aspose.slides/glow/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Mewakili efek Glow, di mana outline berwarna yang kabur ditambahkan di luar tepi objek.
## Metode

| Method | Description |
| --- | --- |
| [getRadius()](#getRadius--) | Radius. |
| [setRadius(double value)](#setRadius-double-) | Radius. |
| [getColor()](#getColor--) | Format warna. |
| [getEffective()](#getEffective--) | Mendapatkan data efek Glow yang efektif dengan pewarisan diterapkan. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah [Glow](../../com.aspose.slides/glow) yang ditentukan sama dengan [Glow](../../com.aspose.slides/glow) saat ini. |
| [hashCode()](#hashCode--) | Berfungsi sebagai fungsi hash untuk tipe tertentu. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Radius. Baca/tulis double.

**Mengembalikan:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Radius. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Format warna. Hanya-baca [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```

Mendapatkan data efek Glow yang efektif dengan pewarisan diterapkan.

**Mengembalikan:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - Sebuah [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).
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

Menentukan apakah [Glow](../../com.aspose.slides/glow) yang ditentukan sama dengan [Glow](../../com.aspose.slides/glow) saat ini.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | [Glow](../../com.aspose.slides/glow) untuk dibandingkan. |

**Mengembalikan:**
boolean - true jika objek sama; jika tidak, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Berfungsi sebagai fungsi hash untuk tipe tertentu.

**Mengembalikan:**
int - Kode hash untuk objek saat ini.