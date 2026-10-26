---
title: IGradientFormatEffectiveData
second_title: Aspose.Slides for Android üzerinden Java API Referansı
description: Etkili degrade doldurma özelliklerini içeren değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/igradientformateffectivedata/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

Etkin degrade doldurma özelliklerini içeren değiştirilemez nesne.

--------------------

Bu arayüz, [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) ve [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)'nin bir parçası olarak kullanılır.
## Yöntemler

| Method | Description |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Bir degrade için çevrim modunu döndürür. |
| [getGradientDirection()](#getGradientDirection--) | Bir degrade stilini döndürür. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Bir degrade açısını döndürür. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Bir degrade'nin ölçeklenip ölçeklenmediğini belirler. |
| [getGradientShape()](#getGradientShape--) | Bir degrade şekli döndürür. |
| [getGradientStops()](#getGradientStops--) | Degrade duraklarının koleksiyonunu döndürür. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

Bir degrade için çevrim modunu döndürür. Salt okunur [TileFlip](../../com.aspose.slides/tileflip).

**Döndürür:**
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

Bir degrade stilini döndürür. Salt okunur [GradientDirection](../../com.aspose.slides/gradientdirection).

**Döndürür:**
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

Bir degrade açısını döndürür. Salt okunur float.

**Döndürür:**
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```

Bir degrade'nin ölçeklenip ölçeklenmediğini belirler. Salt okunur boolean.

**Döndürür:**
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```

Bir degrade şekli döndürür. Salt okunur [GradientShape](../../com.aspose.slides/gradientshape).

**Döndürür:**
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```

Degrade duraklarının koleksiyonunu döndürür. Salt okunur [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata).

**Döndürür:**
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)