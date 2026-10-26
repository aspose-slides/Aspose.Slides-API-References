---
title: IGradientFormatEffectiveData
second_title: Aspose.Slides for Java API Referansı
description: Etkili gradient doldurma özelliklerini içeren değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/igradientformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

Etkili gradient doldurma özelliklerini içeren değiştirilemez nesne.

--------------------

Bu arayüz, [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) ve [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata) öğelerinin bir parçası olarak kullanılır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Bir gradient için çevirme modunu döndürür. |
| [getGradientDirection()](#getGradientDirection--) | Bir gradientin stilini döndürür. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Bir gradientin açısını döndürür. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Bir gradientin ölçeklenip ölçeklenmediğini belirler. |
| [getGradientShape()](#getGradientShape--) | Bir gradientin şeklini döndürür. |
| [getGradientStops()](#getGradientStops--) | Gradient duraklarının koleksiyonunu döndürür. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```


Bir gradient için çevirme modunu döndürür. Salt okunur [TileFlip](../../com.aspose.slides/tileflip).

**Döndürür:**
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```


Bir gradientin stilini döndürür. Salt okunur [GradientDirection](../../com.aspose.slides/gradientdirection).

**Döndürür:**
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```


Bir gradientin açısını döndürür. Salt okunur float.

**Döndürür:**
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```


Bir gradientin ölçeklenip ölçeklenmediğini belirler. Salt okunur boolean.

**Döndürür:**
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```


Bir gradientin şeklini döndürür. Salt okunur [GradientShape](../../com.aspose.slides/gradientshape).

**Döndürür:**
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```


Gradient duraklarının koleksiyonunu döndürür. Salt okunur [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata).

**Döndürür:**
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)