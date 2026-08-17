---
title: GrayScale
second_title: Aspose.Slides for Java API Referansı
description: Gri Ton efektini temsil eder.
type: docs
url: /tr/com.aspose.slides/grayscale/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IGrayScale](../../com.aspose.slides/igrayscale), com.aspose.slides.IVisualEffect
```
public final class GrayScale extends ImageTransformOperation implements IGrayScale, IVisualEffect
```

Bir Gri Ton efekti temsil eder. Tüm efekt renk değerlerini, parlaklıklarına karşılık gelen bir gri tonuna dönüştürür. Etkinin alfa (opaklık) değerleri etkilenmez.
## Metotlar

| Yöntem | Açıklama |
| --- | --- |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili Gri Ton efekti verilerini alır. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [GrayScale](../../com.aspose.slides/grayscale)'in mevcut [GrayScale](../../com.aspose.slides/grayscale) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tip için hash işlevi olarak hizmet eder. |
### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```

Kalıtım uygulanmış etkili Gri Ton efekti verilerini alır.

**Döndürür:**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - A [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Belirtilen [GrayScale](../../com.aspose.slides/grayscale)'in mevcut [GrayScale](../../com.aspose.slides/grayscale) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [GrayScale](../../com.aspose.slides/grayscale). |

**Döndürür:**
boolean - nesneler eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Belirli bir tip için hash işlevi olarak hizmet eder.

**Döndürür:**
int - mevcut nesne için bir hash kodu.