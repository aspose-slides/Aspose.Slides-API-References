---
title: ColorReplace
second_title: Aspose.Slides for Android için Java API Referansı
description: Renk Değiştirme etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/colorreplace/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

Color Replacement etkisini temsil eder. Tüm etki renkleri sabit bir renge değiştirilir. Alfa değerleri etkilenmez.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getColor()](#getColor--) | Her pikselin rengini değiştirecek renk formatını döndürür. |
| [getEffective()](#getEffective--) | Kalıtım uygulanarak etkili Color Replacement efekti verilerini alır. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [ColorReplace](../../com.aspose.slides/colorreplace)'in mevcut [ColorReplace](../../com.aspose.slides/colorreplace) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tip için hash işlevi olarak hizmet eder. |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Her pikselin rengini değiştirecek renk formatını döndürür. Salt okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```

Kalıtım uygulanarak etkili Color Replacement efekti verilerini alır.

**Döndürür:**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - A [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
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

Belirtilen [ColorReplace](../../com.aspose.slides/colorreplace)'in mevcut [ColorReplace](../../com.aspose.slides/colorreplace) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [ColorReplace](../../com.aspose.slides/colorreplace). |

**Döndürür:**
boolean - nesneler eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Belirli bir tip için hash işlevi olarak hizmet eder.

**Döndürür:**
int - Mevcut nesne için bir hash kodu.