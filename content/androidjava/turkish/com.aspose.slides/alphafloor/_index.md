---
title: AlphaFloor
second_title: Aspose.Slides for Android via Java API Referansı
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

Alpha Floor etkisini temsil eder. %100'den az Alpha (opaklık) değerleri sıfıra değiştirilir. Başka bir deyişle, kısmen şeffaf olan her şey tamamen şeffaf hâle gelir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Alpha Floor effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaFloor](../../com.aspose.slides/alphafloor) is equal to the current [AlphaFloor](../../com.aspose.slides/alphafloor). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```


Gets effective Alpha Floor effect data with the inheritance applied.

**Döndürür:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - A [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen [AlphaFloor](../../com.aspose.slides/alphafloor)'ın mevcut [AlphaFloor](../../com.aspose.slides/alphafloor)'a eşit olup olmadığını belirler.

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


Mevcut nesne için bir karma kodu.

**Döndürür:**
int - Mevcut nesne için bir karma kodu.