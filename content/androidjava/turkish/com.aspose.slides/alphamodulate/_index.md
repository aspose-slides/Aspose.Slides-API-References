---
title: AlphaModulate
second_title: Aspose.Slides for Android via Java API Referansı
description: Alpha Modulate etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/alphamodulate/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IAlphaModulate](../../com.aspose.slides/ialphamodulate), com.aspose.slides.IVisualEffect
```
public final class AlphaModulate extends ImageTransformOperation implements IAlphaModulate, IVisualEffect
```

Bir Alpha Modulate etkisini temsil eder. Etkinin alfa (opaklık) değerleri sabit bir yüzde ile çarpılır. Etki konteyneri, modüle edilecek alfa değerlerini içeren bir etki belirtir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili Alpha Modulate etki verilerini alır. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [AlphaModulate](../../com.aspose.slides/alphamodulate)'nin mevcut [AlphaModulate](../../com.aspose.slides/alphamodulate) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tip için bir karma fonksiyonu olarak hizmet verir. |
### getEffective() {#getEffective--}
```
public final IAlphaModulateEffectiveData getEffective()
```


Etkili Alpha Modulate etki verilerini kalıtım uygulanmış şekilde alır.

**Döndürür:**
[IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata) - Bir [IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen [AlphaModulate](../../com.aspose.slides/alphamodulate)'nin mevcut [AlphaModulate](../../com.aspose.slides/alphamodulate) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [AlphaModulate](../../com.aspose.slides/alphamodulate). |

**Döndürür:**
boolean - nesneler eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Belirli bir tip için bir karma fonksiyonu olarak hizmet verir.

**Döndürür:**
int - Mevcut nesne için bir karma kodu.