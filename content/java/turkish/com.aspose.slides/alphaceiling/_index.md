---
title: AlphaCeiling
second_title: Aspose.Slides for Java API Referansı
description: Alpha Ceiling efektini temsil eder.
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

Alpha Ceiling etkisini temsil eder. Alpha (opacity) değerleri sıfırdan büyük olduğunda %100'e değiştirilir. Başka bir deyişle, kısmen opak olan her şey tamamen opak olur.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEffective()](#getEffective--) | Kalıtım uygulanarak etkili Alpha Ceiling etkisi verilerini alır. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [AlphaCeiling](../../com.aspose.slides/alphaceiling)'in mevcut [AlphaCeiling](../../com.aspose.slides/alphaceiling) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tip için bir hash işlevi olarak hizmet eder. |

### getEffective() {#getEffective--}
```
public final IAlphaCeilingEffectiveData getEffective()
```

Kalıtım uygulanarak etkili Alpha Ceiling etkisi verilerini alır.

**Döndürür:**
[IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata) - Bir [IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Belirtilen [AlphaCeiling](../../com.aspose.slides/alphaceiling)'in mevcut [AlphaCeiling](../../com.aspose.slides/alphaceiling) ile eşit olup olmadığını belirler.

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