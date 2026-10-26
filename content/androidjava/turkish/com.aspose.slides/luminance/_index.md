---
title: Luminance
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Luminance etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/luminance/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ILuminance](../../com.aspose.slides/iluminance), com.aspose.slides.IVisualEffect
```
public final class Luminance extends ImageTransformOperation implements ILuminance, IVisualEffect
```

Luminans etkisini temsil eder. Parlaklık, tüm renkleri beyaza veya siyaha doğru lineer olarak kaydırır. Kontrast, tüm renkleri birbirine daha yakın ya da daha uzak olacak şekilde ölçeklendirir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEffective()](#getEffective--) | Uygulanan kalıtım ile etkili Luminans etkisi verilerini alır. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [Luminance](../../com.aspose.slides/luminance) öğesinin mevcut [Luminance](../../com.aspose.slides/luminance) öğesiyle eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tür için bir hash işlevi olarak hizmet eder. |
### getEffective() {#getEffective--}
```
public final ILuminanceEffectiveData getEffective()
```


Uygulanan kalıtım ile etkili Luminans etkisi verilerini alır.

**Döndürür:**
[ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata) - A [ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen [Luminance](../../com.aspose.slides/luminance) öğesinin mevcut [Luminance](../../com.aspose.slides/luminance) öğesiyle eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [Luminance](../../com.aspose.slides/luminance). |

**Döndürür:**
boolean - nesneler eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Belirli bir tür için bir hash işlevi olarak hizmet eder.

**Döndürür:**
int - mevcut nesne için bir hash kodu.