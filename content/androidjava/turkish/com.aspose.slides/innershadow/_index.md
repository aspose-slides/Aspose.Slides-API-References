---
title: InnerShadow
second_title: Aspose.Slides for Android üzerinden Java API Referansı
description: İç Gölge etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/innershadow/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IInnerShadow](../../com.aspose.slides/iinnershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class InnerShadow implements IInnerShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

İç Gölge etkisini temsil eder.
## Metotlar

| Metod | Açıklama |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Bulanıklaştırma yarıçapı. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Bulanıklaştırma yarıçapı. |
| [getDirection()](#getDirection--) | Gölgenin yönü. |
| [setDirection(float value)](#setDirection-float-) | Gölgenin yönü. |
| [getDistance()](#getDistance--) | Gölgenin mesafesi. |
| [setDistance(double value)](#setDistance-double-) | Gölgenin mesafesi. |
| [getShadowColor()](#getShadowColor--) | Gölgenin rengi. |
| [getEffective()](#getEffective--) | Uygulanan kalıtım ile etkili İç Gölge etkisi verilerini alır. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [InnerShadow](../../com.aspose.slides/innershadow) öğesinin geçerli [InnerShadow](../../com.aspose.slides/innershadow) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tür için bir karma işlevi olarak hizmet eder. |
### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

Bulanıklaştırma yarıçapı. Okunabilir/Yazılabilir double.

**Döndürür:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

Bulanıklaştırma yarıçapı. Okunabilir/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public final float getDirection()
```

Gölgenin yönü. Okunabilir/Yazılabilir float.

**Döndürür:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

Gölgenin yönü. Okunabilir/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```

Gölgenin mesafesi. Okunabilir/Yazılabilir double.

**Döndürür:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

Gölgenin mesafesi. Okunabilir/Yazılabilir double.

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
### getEffective() {#getEffective--}
```
public final IInnerShadowEffectiveData getEffective()
```

Uygulanan kalıtım ile etkili İç Gölge etkisi verilerini alır.

**Döndürür:**
[IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata) - Bir [IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata).
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

IPresentationComponent üst nesnesini döndürür. Salt-okunur [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Döndürür:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Belirtilen [InnerShadow](../../com.aspose.slides/innershadow) öğesinin geçerli [InnerShadow](../../com.aspose.slides/innershadow) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [InnerShadow](../../com.aspose.slides/innershadow). |

**Döndürür:**
boolean - nesneler eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Belirli bir tür için bir karma işlevi olarak hizmet eder.

**Döndürür:**
int - Geçerli nesne için bir karma kodu.