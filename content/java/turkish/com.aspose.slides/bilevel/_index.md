---
title: BiLevel
second_title: Aspose.Slides for Java API Referansı
description: Bi-Level siyah/beyaz bir efekti temsil eder.
type: docs
url: /tr/com.aspose.slides/bilevel/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

Bi-Level (siyah/beyaz) bir efekti temsil eder. Belirtilen eşik değerinden daha düşük parlaklığa sahip giriş renkleri siyaha dönüştürülür. Belirtilen değerden büyük veya ona eşit parlaklığa sahip giriş renkleri beyaza ayarlanır. Alfa efekt değerleri bu etkiden etkilenmez.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEffective()](#getEffective--) | Uygulanan kalıtımla etkili Bi-Level efekt verilerini alır. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [BiLevel](../../com.aspose.slides/bilevel) öğesinin geçerli [BiLevel](../../com.aspose.slides/bilevel) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tip için bir karma işlevi olarak hizmet eder. |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```


Uygulanan kalıtımla etkili Bi-Level efekt verilerini alır.

**Döndürür:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - Bir [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen [BiLevel](../../com.aspose.slides/bilevel) öğesinin geçerli [BiLevel](../../com.aspose.slides/bilevel) ile eşit olup olmadığını belirler.

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


Belirli bir tip için bir karma işlevi olarak hizmet eder.

**Döndürür:**
int - Geçerli nesne için bir karma kodu.