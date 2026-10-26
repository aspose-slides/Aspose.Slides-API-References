---
title: FillOverlay
second_title: Aspose.Slides for Java API Referansı
description: Bir Fill Overlay etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/filloverlay/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

Bir Fill Overlay etkisini temsil eder. Fill overlay, bir nesne için ek bir doldurma belirtmek ve iki doldurmayı birleştirmek için kullanılabilir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Doldurma biçimi. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili Fill Overlay veri setini alır. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [FillOverlay](../../com.aspose.slides/filloverlay)'in geçerli [FillOverlay](../../com.aspose.slides/filloverlay) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tür için hash işlevi sağlar. |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Doldurma biçimi. Yalnızca okunur [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBlend() {#getBlend--}
```
public final int getBlend()
```

FillBlendMode. Okunur/yazılır [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Döndürür:**
int
### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```

FillBlendMode. Okunur/yazılır [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```

Kalıtım uygulanmış etkili Fill Overlay veri setini alır.

**Döndürür:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - Bir [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Sürüm. Yalnızca okunur long.

**Döndürür:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Belirtilen [FillOverlay](../../com.aspose.slides/filloverlay)'in geçerli [FillOverlay](../../com.aspose.slides/filloverlay) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [FillOverlay](../../com.aspose.slides/filloverlay). |

**Döndürür:**
boolean - nesneler eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Belirli bir tür için hash işlevi sağlar.

**Döndürür:**
int - Geçerli nesne için bir karma kodu.