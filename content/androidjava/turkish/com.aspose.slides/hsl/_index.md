---
title: HSL
second_title: Aspose.Slides Android için Java API Referansı
description: Hue/Saturation/Luminance etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/hsl/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IHSL](../../com.aspose.slides/ihsl), com.aspose.slides.IVisualEffect
```
public final class HSL extends ImageTransformOperation implements IHSL, IVisualEffect
```

Hue/Saturation/Luminance etkisini temsil eder. Hue, saturation ve luminance her biri mevcut değerine göre ayarlanabilir.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili Hue/Saturation/Luminance efekt verilerini alır. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [HSL](../../com.aspose.slides/hsl)'nin mevcut [HSL](../../com.aspose.slides/hsl) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tür için bir hash işlevi olarak hizmet verir. |
### getEffective() {#getEffective--}
```
public final IHSLEffectiveData getEffective()
```


Kalıtım uygulanmış etkili Hue/Saturation/Luminance efekt verilerini alır.

**Dönüş Değeri:**
[IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata) - Bir [IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen [HSL](../../com.aspose.slides/hsl)'nin mevcut [HSL](../../com.aspose.slides/hsl) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [HSL](../../com.aspose.slides/hsl). |

**Dönüş Değeri:**
boolean - nesneler eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Belirli bir tür için bir hash işlevi olarak hizmet verir.

**Dönüş Değeri:**
int - mevcut nesne için bir hash kodu.