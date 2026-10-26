---
title: Glow
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili efek Glow di mana outline berwarna yang buram ditambahkan di luar tepi objek.
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

Mewakili efek Glow, di mana outline berwarna yang buram ditambahkan di luar tepi objek.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getRadius()](#getRadius--) | Jari-jari. |
| [setRadius(double value)](#setRadius-double-) | Jari-jari. |
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

Jari-jari. Baca/tulis double .

**Mengembalikan:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Jari-jari. Baca/tulis double .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Format warna. Baca-saja [IColorFormat](../../com.aspose.slides/icolorformat).

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

Menentukan apakah [Glow](../../com.aspose.slides/glow) yang ditentukan sama dengan [Glow](../../com.aspose.slides/glow) saat ini.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | [Glow](../../com.aspose.slides/glow) untuk dibandingkan. |

**Mengembalikan:**
boolean - true jika objek sama; lainnya, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Berfungsi sebagai fungsi hash untuk tipe tertentu.

**Mengembalikan:**
int - Kode hash untuk objek saat ini.