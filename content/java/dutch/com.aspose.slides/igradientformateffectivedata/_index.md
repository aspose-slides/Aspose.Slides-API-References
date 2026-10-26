---
title: IGradientFormatEffectiveData
second_title: Aspose.Slides voor Java API-referentie
description: Onveranderbaar object dat effectieve gradientvulling-eigenschappen bevat.
type: docs
url: /nl/com.aspose.slides/igradientformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

Onveranderbaar object dat effectieve gradientvulling-eigenschappen bevat.

--------------------

Deze interface wordt gebruikt als onderdeel van [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) en [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Retourneert de flipping-modus voor een gradient. |
| [getGradientDirection()](#getGradientDirection--) | Retourneert de stijl van een gradient. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Retourneert de hoek van een gradient. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Bepaalt of een gradient geschaald is. |
| [getGradientShape()](#getGradientShape--) | Retourneert de vorm van een gradient. |
| [getGradientStops()](#getGradientStops--) | Retourneert de collectie van gradientstops. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```


Retourneert de flipping-modus voor een gradient. Alleen-lezen [TileFlip](../../com.aspose.slides/tileflip).

**Retour:**  
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```


Retourneert de stijl van een gradient. Alleen-lezen [GradientDirection](../../com.aspose.slides/gradientdirection).

**Retour:**  
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```


Retourneert de hoek van een gradient. Alleen-lezen float.

**Retour:**  
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```


Bepaalt of een gradient geschaald is. Alleen-lezen boolean.

**Retour:**  
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```


Retourneert de vorm van een gradient. Alleen-lezen [GradientShape](../../com.aspose.slides/gradientshape).

**Retour:**  
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```


Retourneert de collectie van gradientstops. Alleen-lezen [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata).

**Retour:**  
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)