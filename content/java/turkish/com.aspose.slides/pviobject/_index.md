---
title: PVIObject
second_title: Aspose.Slides için Java API Referansı
description: Nesneler için temel hizmet altyapısını kapsüller ve özellik değeri mirası konusu olabilir.
type: docs
url: /tr/com.aspose.slides/pviobject/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public abstract class PVIObject implements IPVIObject, ISlideComponent
```

Nesneler için temel hizmet altyapısını kapsüller ve özellik değeri mirası konusu olabilir.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen nesneyle karşılaştırır. |
| [hashCode()](#hashCode--) | Hash kodunu döndürür. |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```


Parent_Immediate nesnesini döndürür. Salt okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versiyon. Salt okunur long.

**Döndürür:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPresentationComponent getParent_IPresentationComponent()
```


parent IPresentationComponent nesnesini döndürür. Salt okunur [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Döndürür:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public ISlideComponent getParent_ISlideComponent()
```




**Döndürür:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)
### getSlide() {#getSlide--}
```
public BaseSlide getSlide()
```


Temel slaytı döndürür. Salt okunur [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Döndürür:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```


Sunumu döndürür. Salt okunur [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[Presentation](../../com.aspose.slides/presentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen nesneyle karşılaştırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak nesne. |

**Döndürür:**
boolean - Nesneler eşitse true, aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash kodunu döndürür.

**Döndürür:**
int - Hash kodu.