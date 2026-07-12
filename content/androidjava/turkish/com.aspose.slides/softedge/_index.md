---
title: SoftEdge
second_title: Aspose.Slides for Android Java API Referansı
description: Yumuşak kenar etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/softedge/
---
**Kalıtım:**
java.lang.Object

**Tüm Gerçekleştirilen Arabirimler:**
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Yumuşak kenar efekti temsil eder. Şeklin kenarları bulanıklaşmıştır, ancak dolgu etkilenmemiştir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRadius()](#getRadius--) | Kenarlara uygulanacak bulanıklık yarıçapını belirtir. |
| [setRadius(double value)](#setRadius-double-) | Kenarlara uygulanacak bulanıklık yarıçapını belirtir. |
| [getEffective()](#getEffective--) | Uygulanan kalıtım ile etkili Soft Edge efekti verilerini alır. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [SoftEdge](../../com.aspose.slides/softedge) öğesinin mevcut [SoftEdge](../../com.aspose.slides/softedge) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tip için hash işlevi olarak hizmet eder. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Kenarlara uygulanacak bulanıklık yarıçapını belirtir. Okunur/yazılır double.

**Döndürür:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Kenarlara uygulanacak bulanıklık yarıçapını belirtir. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```

Uygulanan kalıtım ile etkili Soft Edge efekti verilerini alır.

**Döndürür:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - A [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).
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

Versiyon. Salt okunur long.

**Döndürür:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

IPresentationComponent üst nesnesini döndürür. Salt okunur [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Döndürür:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Belirtilen [SoftEdge](../../com.aspose.slides/softedge) öğesinin mevcut [SoftEdge](../../com.aspose.slides/softedge) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [SoftEdge](../../com.aspose.slides/softedge). |

**Döndürür:**
boolean - nesneler eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Belirli bir tip için hash işlevi olarak hizmet eder.

**Döndürür:**
int - Mevcut nesne için bir hash kodu.