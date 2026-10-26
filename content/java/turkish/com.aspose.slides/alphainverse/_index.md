---
title: AlphaInverse
second_title: Aspose.Slides için Java API Referansı
description: Alfa ters etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/alphainverse/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IAlphaInverse](../../com.aspose.slides/ialphainverse), com.aspose.slides.IVisualEffect
```
public final class AlphaInverse extends ImageTransformOperation implements IAlphaInverse, IVisualEffect
```

Alfa ters etkisini temsil eder. Alfa (opaklık) değerleri %100'den çıkarılarak tersine çevrilir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEffective()](#getEffective--) | Uygulanan kalıtım ile etkili Alfa Ters etkisi verilerini alır. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [AlphaInverse](../../com.aspose.slides/alphainverse)'nin mevcut [AlphaInverse](../../com.aspose.slides/alphainverse) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tip için bir karma işlevi olarak hizmet verir. |
### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```


Uygulanan kalıtım ile etkili Alfa Ters etkisi verilerini alır.

**Döndürür:**
[IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata) - Bir [IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Sürüm. Salt-okunur uzun.

**Döndürür:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen [AlphaInverse](../../com.aspose.slides/alphainverse)'nin mevcut [AlphaInverse](../../com.aspose.slides/alphainverse) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [AlphaInverse](../../com.aspose.slides/alphainverse). |

**Döndürür:**
boolean - nesneler eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Belirli bir tip için bir karma işlevi olarak hizmet verir.

**Döndürür:**
int - Geçerli nesne için bir karma kodu.