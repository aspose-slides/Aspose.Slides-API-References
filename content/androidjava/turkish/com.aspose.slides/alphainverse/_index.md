---
title: AlphaInverse
second_title: Aspose.Slides for Android via Java API Referansı
description: Alfa Ters etkisini temsil eder.
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

Alfa Ters etkiyi temsil eder. Alfa (opaklık) değerleri %100'den çıkarılarak tersine çevrilir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili Alpha Inverse etki verilerini alır. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [AlphaInverse](../../com.aspose.slides/alphainverse)'nin mevcut [AlphaInverse](../../com.aspose.slides/alphainverse) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tip için bir hash fonksiyonu olarak hizmet eder. |
### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```

Kalıtım uygulanmış etkili Alpha Inverse etki verilerini alır.

**Döndürür:**
[IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata) - Bir [IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Sürüm. Salt okunur long.

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

Belirli bir tip için bir hash fonksiyonu olarak hizmet eder.

**Döndürür:**
int - Mevcut nesne için bir hash kodu.