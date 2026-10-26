---
title: ColorReplace
second_title: Aspose.Slides için Java API Referansı
description: Bir Renk Değiştirme etkisini temsil eder.
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

Bir Renk Değiştirme etkisini temsil eder. Tüm etki renkleri sabit bir renge değiştirilir. Alfa değerleri etkilenmez.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getColor()](#getColor--) | Her pikselin rengini değiştirecek renk formatını döndürür. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili Renk Değiştirme etkisi verilerini alır. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [ColorReplace](../../com.aspose.slides/colorreplace) öğesinin mevcut [ColorReplace](../../com.aspose.slides/colorreplace) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tür için hash işlevi olarak hizmet eder. |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Her pikselin rengini değiştirecek renk formatını döndürür. Salt-okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Dönüş değeri:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```

Kalıtım uygulanmış etkili Renk Değiştirme etkisi verilerini alır.

**Dönüş değeri:**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - Bir [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Sürüm. Salt-okunur long.

**Dönüş değeri:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Belirtilen [ColorReplace](../../com.aspose.slides/colorreplace) öğesinin mevcut [ColorReplace](../../com.aspose.slides/colorreplace) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [ColorReplace](../../com.aspose.slides/colorreplace). |

**Dönüş değeri:**
boolean - nesneler eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Belirli bir tür için hash işlevi olarak hizmet eder.

**Dönüş değeri:**
int - Geçerli nesne için bir hash kodu.