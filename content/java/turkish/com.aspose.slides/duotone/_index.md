---
title: Duotone
second_title: Aspose.Slides for Java API Referansı
description: Bir Duotone etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/duotone/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

Bir Duotone etkisini temsil eder. Her piksel için, yeni rengi belirlemek üzere lineer bir enterpolasyonla Color1 ve Color2'yi birleştirir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getColor1()](#getColor1--) | Karanlık pikseller için hedef renk formatını döndürür. |
| [getColor2()](#getColor2--) | Açık pikseller için hedef renk formatını döndürür. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili Duotone efekt verilerini alır. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [Duotone](../../com.aspose.slides/duotone)'in geçerli [Duotone](../../com.aspose.slides/duotone) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tip için hash işlevi olarak hizmet eder. |
### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```


Karanlık pikseller için hedef renk formatını döndürür. Yalnızca okuma [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```


Açık pikseller için hedef renk formatını döndürür. Yalnızca okuma [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```


Kalıtım uygulanmış etkili Duotone efekt verilerini alır.

**Döndürür:**
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - Bir [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Sürüm. Yalnızca okuma long.

**Döndürür:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen [Duotone](../../com.aspose.slides/duotone)'in geçerli [Duotone](../../com.aspose.slides/duotone) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [Duotone](../../com.aspose.slides/duotone). |

**Döndürür:**
boolean - nesneler eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Belirli bir tip için hash işlevi olarak hizmet eder.

**Döndürür:**
int - Geçerli nesne için bir hash kodu.