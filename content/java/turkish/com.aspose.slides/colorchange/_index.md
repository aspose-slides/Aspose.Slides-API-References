---
title: ColorChange
second_title: Aspose.Slides for Java API Referansı
description: Bir Renk Değişikliği efekti temsil eder.
type: docs
url: /tr/com.aspose.slides/colorchange/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

Bir Renk Değişikliği efekti temsil eder. FromColor örnekleri ToColor örnekleriyle değiştirilir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFromColor()](#getFromColor--) | Değiştirilecek renk. |
| [getToColor()](#getToColor--) | Yerine konulacak renk. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili Renk Değişikliği efekti verilerini alır. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [ColorChange](../../com.aspose.slides/colorchange) mevcut [ColorChange](../../com.aspose.slides/colorchange) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tip için bir hash fonksiyonu olarak hizmet eder. |
### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```


Değiştirilecek renk. Salt okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```


Yerine konulacak renk. Salt okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```


Kalıtım uygulanmış etkili Renk Değişikliği efekti verilerini alır.

**Döndürür:**
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - Bir [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versiyon. Salt okunur long.

**Döndürür:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen [ColorChange](../../com.aspose.slides/colorchange) mevcut [ColorChange](../../com.aspose.slides/colorchange) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [ColorChange](../../com.aspose.slides/colorchange). |

**Döndürür:**
boolean - nesneler eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Belirli bir tip için bir hash fonksiyonu olarak hizmet eder.

**Döndürür:**
int - Geçerli nesne için bir hash kodu.