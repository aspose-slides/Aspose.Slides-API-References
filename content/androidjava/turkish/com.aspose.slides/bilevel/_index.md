---
title: BiLevel
second_title: Aspose.Slides for Android üzerinden Java API Referansı
description: Bi-Level siyah/beyaz bir efekti temsil eder.
type: docs
url: /tr/com.aspose.slides/bilevel/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

Bi-Level (siyah/beyaz) bir efekti temsil eder. Belirtilen eşik değerinden daha düşük parlaklığa sahip giriş renkleri siyahe dönüştürülür. Belirtilen değerden eşit veya daha yüksek parlaklığa sahip giriş renkleri beyaza ayarlanır. Alfa efekt değerleri bu etkiden etkilenmez.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili Bi-Level efekt verilerini alır. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [BiLevel](../../com.aspose.slides/bilevel)'in mevcut [BiLevel](../../com.aspose.slides/bilevel) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tür için hash işlevi olarak hizmet eder. |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

Kalıtım uygulanmış etkili Bi-Level efekt verilerini alır.

**Döndürür:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - A [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Belirtilen [BiLevel](../../com.aspose.slides/bilevel)'in mevcut [BiLevel](../../com.aspose.slides/bilevel) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [BiLevel](../../com.aspose.slides/bilevel). |

**Döndürür:**
boolean - nesneler eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Belirli bir tür için hash işlevi olarak hizmet eder.

**Döndürür:**
int - mevcut nesne için bir hash kodu.