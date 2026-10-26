---
title: IGradientFormatEffectiveData
second_title: Aspose.Slides voor Android via Java API-referentie
description: Onveranderlijk object dat effectieve gradientvullings-eigenschappen bevat.
type: docs
url: /nl/com.aspose.slides/igradientformateffectivedata/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

Onveranderlijk object dat effectieve gradientvullings-eigenschappen bevat.

--------------------

Dit interface wordt gebruikt als onderdeel van [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) en [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Retourneert de omslagmodus voor een gradient. |
| [getGradientDirection()](#getGradientDirection--) | Retourneert de stijl van een gradient. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Retourneert de hoek van een gradient. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Bepaalt of een gradient wordt geschaald. |
| [getGradientShape()](#getGradientShape--) | Retourneert de vorm van een gradient. |
| [getGradientStops()](#getGradientStops--) | Retourneert de collectie van gradientstops. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```


Retourneert de omslagmodus voor een gradient. Alleen-lezen [TileFlip](../../com.aspose.slides/tileflip).

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


Bepaalt of een gradient wordt geschaald. Alleen-lezen boolean.

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