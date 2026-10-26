---
title: PresetShadow
second_title: Aspose.Slides for Java API Referansı
description: Preset Gölge efektini temsil eder.
type: docs
url: /tr/com.aspose.slides/presetshadow/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IPresetShadow](../../com.aspose.slides/ipresetshadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class PresetShadow implements IPresetShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Preset Gölge efektini temsil eder.
## Yöntemler

| Metod | Açıklama |
| --- | --- |
| [getDirection()](#getDirection--) | Direction of shadow. |
| [setDirection(float value)](#setDirection-float-) | Direction of shadow. |
| [getDistance()](#getDistance--) | Distance of shadow. |
| [setDistance(double value)](#setDistance-double-) | Distance of shadow. |
| [getShadowColor()](#getShadowColor--) | Color of shadow. |
| [getPreset()](#getPreset--) | Preset. |
| [setPreset(int value)](#setPreset-int-) | Preset. |
| [getEffective()](#getEffective--) | Gets effective Preset Shadow effect data with the inheritance applied. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [PresetShadow](../../com.aspose.slides/presetshadow) is equal to the current [PresetShadow](../../com.aspose.slides/presetshadow). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getDirection() {#getDirection--}
```
public final float getDirection()
```

Gölgenin yönü. Okunur/Yazılabilir  float .

**Döndürür:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

Gölgenin yönü. Okunur/Yazılabilir  float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```

Gölgenin mesafesi. Okunur/Yazılabilir  double .

**Döndürür:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

Gölgenin mesafesi. Okunur/Yazılabilir  double .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

Gölgenin rengi. Yalnızca okuma [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public final int getPreset()
```

Ön ayar. Okunur/Yazılabilir [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Döndürür:**
int
### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```

Ön ayar. Okunur/Yazılabilir [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```

Kalitim uygulanmış etkili Preset Shadow efekti verilerini alır.

**Döndürür:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - Bir [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Yalnızca okuma IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Versiyon. Yalnızca okuma long.

**Döndürür:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

IPresentationComponent üst nesnesini döndürür. Yalnızca okuma [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Döndürür:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Belirtilen [PresetShadow](../../com.aspose.slides/presetshadow)'in geçerli [PresetShadow](../../com.aspose.slides/presetshadow) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | The [PresetShadow](../../com.aspose.slides/presetshadow) to compare. |
**Döndürür:**
boolean - objeler eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Belirli bir tür için bir karma işlevi olarak hizmet eder.

**Döndürür:**
int - Geçerli nesne için bir karma kodu.