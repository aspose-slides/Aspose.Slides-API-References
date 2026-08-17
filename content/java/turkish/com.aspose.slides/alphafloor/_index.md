---
title: AlphaFloor
second_title: Aspose.Slides Java API Referansı
description: Alpha Floor etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/alphafloor/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public final class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualEffect
```

Bir Alpha Floor etkisini temsil eder. %100'den düşük Alfa (opaklık) değerleri sıfıra ayarlanır. Başka bir deyişle, kısmen şeffaf olan her şey tamamen şeffaf hâle gelir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEffective()](#getEffective--) | Uygulamaya alınmış kalıtımla etkili Alpha Floor etkisi verilerini alır. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [AlphaFloor](../../com.aspose.slides/alphafloor)'nin mevcut [AlphaFloor](../../com.aspose.slides/alphafloor) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tip için hash işlevi olarak hizmet verir. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```


Uygulamaya alınmış kalıtımla etkili Alpha Floor etkisi verilerini alır.

**Döndürür:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - Bir [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen [AlphaFloor](../../com.aspose.slides/alphafloor)'nin mevcut [AlphaFloor](../../com.aspose.slides/alphafloor) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [AlphaFloor](../../com.aspose.slides/alphafloor). |

**Döndürür:**
boolean - nesneler eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Belirli bir tip için hash işlevi olarak hizmet verir.

**Döndürür:**
int - mevcut nesne için bir hash kodu.