---
title: Tint
second_title: Android için Aspose.Slides via Java API Referansı
description: Bir Tint efektini temsil eder.
type: docs
url: /tr/com.aspose.slides/tint/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ITint](../../com.aspose.slides/itint), com.aspose.slides.IVisualEffect
```
public final class Tint extends ImageTransformOperation implements ITint, IVisualEffect
```

Bir Tint etkisini temsil eder. Etkinin renk değerlerini belirtilen miktarda tona doğru/tersine kaydırır.

## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getEffective()](#getEffective--) | Miras uygulanmış etkili Tint efekti verisini alır. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [Tint](../../com.aspose.slides/tint)'in mevcut [Tint](../../com.aspose.slides/tint)'e eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tip için bir hash işlevi olarak hizmet eder. |
### getEffective() {#getEffective--}
```
public final ITintEffectiveData getEffective()
```


Miras uygulanmış etkili Tint efekti verisini alır.

**Dönen Değer:**
[ITintEffectiveData](../../com.aspose.slides/itinteffectivedata) - Bir [ITintEffectiveData](../../com.aspose.slides/itinteffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen [Tint](../../com.aspose.slides/tint)'in mevcut [Tint](../../com.aspose.slides/tint)'e eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [Tint](../../com.aspose.slides/tint). |

**Dönen Değer:**
boolean - nesneler eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Belirli bir tip için bir hash işlevi olarak hizmet eder.

**Dönen Değer:**
int - mevcut nesne için bir hash kodu.