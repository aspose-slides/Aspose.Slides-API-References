---
title: FillOverlay
second_title: Aspose.Slides for Android Java API Referansı
description: Bir Dolgu Örtüsü etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/filloverlay/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

Bir Dolgu Örtüsü etkisini temsil eder. Dolgu örtüsü, bir nesne için ek bir dolgu belirtmek ve iki dolguyu birleştirmek için kullanılabilir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Dolgu biçimi. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | Kalıtım uygulanarak etkili Dolgu Örtüsü etkisi verilerini alır. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [FillOverlay](../../com.aspose.slides/filloverlay) öğesinin mevcut [FillOverlay](../../com.aspose.slides/filloverlay) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tür için bir karma işlevi olarak hizmet eder. |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Dolgu biçimi. Salt okunur [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBlend() {#getBlend--}
```
public final int getBlend()
```


FillBlendMode. Okunur/yazılabilir [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Döndürür:**
int
### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```


FillBlendMode. Okunur/yazılabilir [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```


Kalıtım uygulanarak etkili Dolgu Örtüsü etkisi verilerini alır.

**Döndürür:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - Bir [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Sürüm. Salt okunur long.

**Döndürür:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen [FillOverlay](../../com.aspose.slides/filloverlay) öğesinin mevcut [FillOverlay](../../com.aspose.slides/filloverlay) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [FillOverlay](../../com.aspose.slides/filloverlay). |

**Döndürür:**
boolean - nesneler eşitse true, aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Belirli bir tür için bir karma işlevi olarak hizmet eder.

**Döndürür:**
int - Mevcut nesne için bir karma kodu.