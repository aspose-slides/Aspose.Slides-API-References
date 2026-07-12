---
title: Glow
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir nesnenin kenarlarının dışına renkli bulanık bir hat eklenerek bir Glow efekti temsil eder.
type: docs
url: /tr/com.aspose.slides/glow/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Objenin kenarlarının dışına renkli bulanık bir hat eklenerek bir Glow efekti temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getRadius()](#getRadius--) | Yarıçap. |
| [setRadius(double value)](#setRadius-double-) | Yarıçap. |
| [getColor()](#getColor--) | Renk formatı. |
| [getEffective()](#getEffective--) | Miras uygulandığında etkili Glow efekti verilerini alır. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [Glow](../../com.aspose.slides/glow)'nin mevcut [Glow](../../com.aspose.slides/glow) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tip için bir hash işlevi olarak hizmet verir. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Yarıçap. Okunur/yazılır  double .

**Döndürür:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Yarıçap. Okunur/yazılır  double .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Renk formatı. Salt okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```


Miras uygulandığında etkili Glow efekti verilerini alır.

**Döndürür:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - A [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate nesnesini döndürür. Salt okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Sürüm. Salt okunur long.

**Döndürür:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Parent IPresentationComponent nesnesini döndürür. Salt okunur [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Döndürür:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen [Glow](../../com.aspose.slides/glow)'nin mevcut [Glow](../../com.aspose.slides/glow) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [Glow](../../com.aspose.slides/glow). |

**Döndürür:**
boolean - nesneler eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Belirli bir tip için bir hash işlevi olarak hizmet verir.

**Döndürür:**
int - Mevcut nesne için bir hash kodu.