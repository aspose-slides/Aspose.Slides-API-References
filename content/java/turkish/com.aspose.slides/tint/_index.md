---
title: Tint
second_title: Aspose.Slides for Java API Referansı
description: Bir Tint etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/tint/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ITint](../../com.aspose.slides/itint), com.aspose.slides.IVisualEffect
```
public final class Tint extends ImageTransformOperation implements ITint, IVisualEffect
```

Tint etkisini temsil eder. Etki renk değerlerini belirtilen miktarda renkten uzaklaştırır ya da ona doğru kaydırır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili Tint etkisi verilerini alır. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [Tint](../../com.aspose.slides/tint)'nin mevcut [Tint](../../com.aspose.slides/tint) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tip için bir karma işlevi olarak hizmet verir. |
### getEffective() {#getEffective--}
```
public final ITintEffectiveData getEffective()
```

Kalıtım uygulanmış etkili Tint etkisi verilerini alır.

**Dönüş:**
[ITintEffectiveData](../../com.aspose.slides/itinteffectivedata) - Bir [ITintEffectiveData](../../com.aspose.slides/itinteffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Belirtilen [Tint](../../com.aspose.slides/tint)'nin mevcut [Tint](../../com.aspose.slides/tint) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [Tint](../../com.aspose.slides/tint). |

**Dönüş:**
boolean - nesneler eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Belirli bir tip için bir karma işlevi olarak hizmet verir.

**Dönüş:**
int - Mevcut nesne için bir karma kodu.