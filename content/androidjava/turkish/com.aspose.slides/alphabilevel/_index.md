---
title: AlphaBiLevel
second_title: Aspose.Slides Android için Java API Referansı
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

Alpha Bi-Level etkisini temsil eder. Eşik değerinden küçük Alpha (Opacity) değerleri 0'a (tamamen şeffaf) ve eşik değerine eşit veya daha büyük Alpha değerleri %100'e (tamamen opak) değiştirilir.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getThreshold()](#getThreshold--) | Etkisinin eşik değerini döndürür. |
| [setThreshold(float value)](#setThreshold-float-) | Etkisinin eşik değerini döndürür. |
| [getEffective()](#getEffective--) | Uygulanan kalıtım ile etkili Alpha Bi-Level efekt verilerini alır. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [AlphaBiLevel](../../com.aspose.slides/alphabilevel)'ın mevcut [AlphaBiLevel](../../com.aspose.slides/alphabilevel) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tip için hash işlevi olarak hizmet verir. |
### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```


Etkisinin eşik değerini döndürür. Okunur/yazılır float.

**Döndürür:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```


Etkisinin eşik değerini döndürür. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```


Uygulanan kalıtım ile etkili Alpha Bi-Level efekt verilerini alır.

**Döndürür:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - bir [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen [AlphaBiLevel](../../com.aspose.slides/alphabilevel)'ın mevcut [AlphaBiLevel](../../com.aspose.slides/alphabilevel) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [AlphaBiLevel](../../com.aspose.slides/alphabilevel). |

**Döndürür:**
boolean - nesneler eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Belirli bir tip için hash işlevi olarak hizmet verir.

**Döndürür:**
int - Mevcut nesne için bir hash kodu.