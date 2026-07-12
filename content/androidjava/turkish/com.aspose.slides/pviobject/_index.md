---
title: PVIObject
second_title: Aspose.Slides for Android için Java API Referansı
description: Nesneler için temel hizmet altyapısını kapsüller; bu nesneler özellik değeri kalıtımının konusu olabilir.
type: docs
url: /tr/com.aspose.slides/pviobject/
---
**Kalıtım:**
java.lang.Object

**Tüm Gerçekleştirilen Arabirimler:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public abstract class PVIObject implements IPVIObject, ISlideComponent
```

Nesneler için temel hizmet altyapısını kapsüller; bu nesneler özellik değeri kalıtımının konusu olabilir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen nesneyle karşılaştırır. |
| [hashCode()](#hashCode--) | Karma kodunu döndürür. |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Yalnızca okuma IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public long getVersion()
```

Sürüm. Yalnızca okuma long.

**Döndürür:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPresentationComponent getParent_IPresentationComponent()
```

Üst IPresentationComponent nesnesini döndürür. Yalnızca okuma [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

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

Temel slaytı döndürür. Yalnızca okuma [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Döndürür:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```

Sunumu döndürür. Yalnızca okuma [IPresentation](../../com.aspose.slides/ipresentation).

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
boolean - True, nesneler eşitse, aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Karma kodunu döndürür.

**Döndürür:**
int - Karma kodu.