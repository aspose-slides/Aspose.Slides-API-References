---
title: AlphaBiLevel
second_title: Aspose.Slides için Java API Referansı
description: Alpha Bi-Level etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/alphabilevel/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

Alpha Bi-Level etkisini temsil eder. Eşik değerinden daha düşük Alpha (Opacity) değerleri 0 (tamamen şeffaf) olarak, eşik değerine eşit veya daha yüksek Alpha değerleri %100 (tamamen opak) olarak değiştirilir.

## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getThreshold()](#getThreshold--) | Etkinin eşiğini döndürür. |
| [setThreshold(float value)](#setThreshold-float-) | Etkinin eşiğini döndürür. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili Alpha Bi-Level efekt verisini alır. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [AlphaBiLevel](../../com.aspose.slides/alphabilevel) öğesinin mevcut [AlphaBiLevel](../../com.aspose.slides/alphabilevel) öğesine eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tür için hash fonksiyonu olarak hizmet eder. |

### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```

Etkisinin eşiğini döndürür. Okunabilir/yazılabilir float.

**Döndürür:**
float

### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```

Etkisinin eşiğini döndürür. Okunabilir/yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```

Uygulanan kalıtım ile etkili Alpha Bi-Level efekt verisini alır.

**Döndürür:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - Bir [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Belirtilen [AlphaBiLevel](../../com.aspose.slides/alphabilevel) öğesinin mevcut [AlphaBiLevel](../../com.aspose.slides/alphabilevel) öğesine eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [AlphaBiLevel](../../com.aspose.slides/alphabilevel). |

**Döndürür:**
boolean - nesneler eşitse true; aksi takdirde false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Belirli bir tür için hash fonksiyonu olarak hizmet eder.

**Döndürür:**
int - Mevcut nesne için bir hash kodu.