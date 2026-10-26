---
title: Glow
second_title: Aspose.Slides for Java API Referansı
description: Nesnenin kenarlarının dışına renkli bulanık bir anahat eklenen bir Glow etkisini temsil eder.
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

Nesnenin kenarlarının dışına renkli bulanık bir anahat eklenen bir Glow etkisini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRadius()](#getRadius--) | Radius. |
| [setRadius(double value)](#setRadius-double-) | Radius. |
| [getColor()](#getColor--) | Color format. |
| [getEffective()](#getEffective--) | Gets effective Glow effect data with the inheritance applied. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [Glow](../../com.aspose.slides/glow) is equal to the current [Glow](../../com.aspose.slides/glow). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Yarıçap. Okunabilir/Yazılabilir  double .

**Döndürür:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Yarıçap. Okunabilir/Yazılabilir  double .

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | double |  |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Renk biçimi. Yalnızca okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```

Gets effective Glow effect data with the inheritance applied.

**Döndürür:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - A [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Yalnızca okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Versiyon. Yalnızca okunur long.

**Döndürür:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

parent IPresentationComponent nesnesini döndürür. Yalnızca okunur [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Döndürür:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Belirtilen [Glow](../../com.aspose.slides/glow)'in mevcut [Glow](../../com.aspose.slides/glow) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [Glow](../../com.aspose.slides/glow). |

**Döndürür:**
boolean - nesneler eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Belirli bir tür için bir hash işlevi olarak hizmet eder.

**Döndürür:**
int - Geçerli nesne için bir hash kodu.