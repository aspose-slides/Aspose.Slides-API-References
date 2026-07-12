---
title: AlphaCeiling
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Alfa Tavan etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/alphaceiling/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IAlphaCeiling](../../com.aspose.slides/ialphaceiling), com.aspose.slides.IVisualEffect
```
public final class AlphaCeiling extends ImageTransformOperation implements IAlphaCeiling, IVisualEffect
```

Alfa Tavan efekti temsil eder. Sıfırdan büyük alfa (opaklık) değerleri %100'e değiştirilir. Başka bir deyişle, kısmen opak olan her şey tam opak hâle gelir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Alpha Ceiling effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaCeiling](../../com.aspose.slides/alphaceiling) is equal to the current [AlphaCeiling](../../com.aspose.slides/alphaceiling). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getEffective() {#getEffective--}
```
public final IAlphaCeilingEffectiveData getEffective()
```


Uygulanan kalıtımla etkili Alfa Tavan efekti verilerini alır.

**Döndürür:**
[IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata) - Bir [IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen [AlphaCeiling](../../com.aspose.slides/alphaceiling) öğesinin mevcut [AlphaCeiling](../../com.aspose.slides/alphaceiling) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [AlphaCeiling](../../com.aspose.slides/alphaceiling). |

**Döndürür:**
boolean - nesneler eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Belirli bir tip için bir hash işlevi olarak hizmet eder.

**Döndürür:**
int - Geçerli nesne için bir hash kodu.