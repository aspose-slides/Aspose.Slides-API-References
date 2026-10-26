---
title: Luminance
second_title: Aspose.Slides for Java API Referansı
description: Luminance etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/luminance/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Uygulanan Arayüzler:**
[com.aspose.slides.ILuminance](../../com.aspose.slides/iluminance), com.aspose.slides.IVisualEffect
```
public final class Luminance extends ImageTransformOperation implements ILuminance, IVisualEffect
```

Luminance etkisini temsil eder. Parlaklık tüm renkleri lineer olarak beyaza ya da siyaha yaklaştırır. Kontrast ise tüm renkleri daha yakın ya da daha uzak hâle getirecek şekilde ölçeklendirir.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getEffective()](#getEffective--) | Miras uygulandıktan sonra etkili Luminance efekt verilerini alır. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [Luminance](../../com.aspose.slides/luminance) mevcut [Luminance](../../com.aspose.slides/luminance) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tür için bir hash işlevi olarak hizmet eder. |
### getEffective() {#getEffective--}
```
public final ILuminanceEffectiveData getEffective()
```


Miras uygulandıktan sonra etkili Luminance efekt verilerini alır.

**Döndürür:**
[ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata) - Bir [ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen [Luminance](../../com.aspose.slides/luminance) öğesinin mevcut [Luminance](../../com.aspose.slides/luminance) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
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