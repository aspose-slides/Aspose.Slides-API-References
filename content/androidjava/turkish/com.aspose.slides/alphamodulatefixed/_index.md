---
title: AlphaModulateFixed
second_title: Aspose.Slides for Android via Java API Referansı
description: Alpha Modulate Fixed etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/alphamodulatefixed/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tüm Gerçekleştirilen Arabirimler:**
[com.aspose.slides.IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed), com.aspose.slides.IVisualEffect
```
public final class AlphaModulateFixed extends ImageTransformOperation implements IAlphaModulateFixed, IVisualEffect
```

Alpha Modulate Fixed etkisini temsil eder. Etki alfası (opaklık) değerleri sabit bir yüzdeyle çarpılır.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getAmount()](#getAmount--) | Etkinin miktarını yüzde olarak döndürür. |
| [setAmount(float value)](#setAmount-float-) | Etkinin miktarını yüzde olarak döndürür. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili Alpha Modulate Fixed efekt verilerini alır. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed)'nin mevcut [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tip için hash işlevi olarak hizmet verir. |
### getAmount() {#getAmount--}
```
public final float getAmount()
```


Etkinin miktarını yüzde olarak döndürür. Okunur/yazılır float.

**Döndürür:**
float
### setAmount(float value) {#setAmount-float-}
```
public final void setAmount(float value)
```


Etkinin miktarını yüzde olarak döndürür. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaModulateFixedEffectiveData getEffective()
```


Kalıtım uygulanmış etkili Alpha Modulate Fixed efekt verilerini alır.

**Döndürür:**
[IAlphaModulateFixedEffectiveData](../../com.aspose.slides/ialphamodulatefixedeffectivedata) - Bir [IAlphaModulateFixedEffectiveData](../../com.aspose.slides/ialphamodulatefixedeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed)'nin mevcut [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed)'yi karşılaştırmak için |

**Döndürür:**
boolean - nesneler eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Belirli bir tip için hash işlevi olarak hizmet verir.

**Döndürür:**
int - Geçerli nesne için bir hash kodu.