---
title: PresetShadow
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili efek Preset Shadow.
type: docs
url: /id/com.aspose.slides/presetshadow/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IPresetShadow](../../com.aspose.slides/ipresetshadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class PresetShadow implements IPresetShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Mewakili efek Preset Shadow.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getDirection()](#getDirection--) | Arah bayangan. |
| [setDirection(float value)](#setDirection-float-) | Arah bayangan. |
| [getDistance()](#getDistance--) | Jarak bayangan. |
| [setDistance(double value)](#setDistance-double-) | Jarak bayangan. |
| [getShadowColor()](#getShadowColor--) | Warna bayangan. |
| [getPreset()](#getPreset--) | Preset. |
| [setPreset(int value)](#setPreset-int-) | Preset. |
| [getEffective()](#getEffective--) | Mendapatkan data efek Preset Shadow yang efektif dengan pewarisan yang diterapkan. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah [PresetShadow](../../com.aspose.slides/presetshadow) yang ditentukan sama dengan [PresetShadow](../../com.aspose.slides/presetshadow) saat ini. |
| [hashCode()](#hashCode--) | Berfungsi sebagai fungsi hash untuk tipe tertentu. |
### getDirection() {#getDirection--}
```
public final float getDirection()
```


Arah bayangan. Baca/tulis  float .

**Mengembalikan:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```


Arah bayangan. Baca/tulis  float .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```


Jarak bayangan. Baca/tulis  double .

**Mengembalikan:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


Jarak bayangan. Baca/tulis  double .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```


Warna bayangan. Baca-saja [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public final int getPreset()
```


Preset. Baca/tulis [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Mengembalikan:**
int
### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```


Preset. Baca/tulis [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```


Mendapatkan data efek Preset Shadow yang efektif dengan pewarisan yang diterapkan.

**Mengembalikan:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - Sebuah [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).
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


Menentukan apakah [PresetShadow](../../com.aspose.slides/presetshadow) yang ditentukan sama dengan [PresetShadow](../../com.aspose.slides/presetshadow) saat ini.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | [PresetShadow](../../com.aspose.slides/presetshadow) untuk dibandingkan. |

**Mengembalikan:**
boolean - true jika objek sama; sebaliknya, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Berfungsi sebagai fungsi hash untuk tipe tertentu.

**Mengembalikan:**
int - Kode hash untuk objek saat ini.