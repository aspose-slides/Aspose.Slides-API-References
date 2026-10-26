---
title: PresetShadow
second_title: Aspose.Slides Android için Java API Referansı
description: Ön ayarlı bir gölge efekti temsil eder.
type: docs
url: /tr/com.aspose.slides/presetshadow/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IPresetShadow](../../com.aspose.slides/ipresetshadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class PresetShadow implements IPresetShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Bir Ön Ayarlı Gölge efekti temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDirection()](#getDirection--) | Gölgenin yönü. |
| [setDirection(float value)](#setDirection-float-) | Gölgenin yönü. |
| [getDistance()](#getDistance--) | Gölgenin mesafesi. |
| [setDistance(double value)](#setDistance-double-) | Gölgenin mesafesi. |
| [getShadowColor()](#getShadowColor--) | Gölgenin rengi. |
| [getPreset()](#getPreset--) | Ön ayar. |
| [setPreset(int value)](#setPreset-int-) | Ön ayar. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili Ön Ayarlı Gölge efekti verilerini alır. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [PresetShadow](../../com.aspose.slides/presetshadow)'in mevcut [PresetShadow](../../com.aspose.slides/presetshadow) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tip için karma fonksiyonu olarak hizmet eder. |
### getDirection() {#getDirection--}
```
public final float getDirection()
```


Gölgenin yönü. Okuma/yazma  float .

**Döndürür:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```


Gölgenin yönü. Okuma/yazma  float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```


Gölgenin mesafesi. Okuma/yazma  double .

**Döndürür:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


Gölgenin mesafesi. Okuma/yazma  double .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```


Gölgenin rengi. Salt-okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public final int getPreset()
```


Ön ayar. Okuma/yazma [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Döndürür:**
int
### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```


Ön ayar. Okuma/yazma [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```


Kalıtım uygulanmış etkili Ön Ayarlı Gölge efekti verilerini alır.

**Döndürür:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - A [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate nesnesini döndürür. Salt-okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Sürüm. Salt-okunur long.

**Döndürür:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


parent IPresentationComponent nesnesini döndürür. Salt-okunur [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Döndürür:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen [PresetShadow](../../com.aspose.slides/presetshadow)'in mevcut [PresetShadow](../../com.aspose.slides/presetshadow) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [PresetShadow](../../com.aspose.slides/presetshadow). |

**Döndürür:**
boolean - nesneler eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Belirli bir tip için karma fonksiyonu olarak hizmet eder.

**Döndürür:**
int - Mevcut nesne için bir karma kodu.