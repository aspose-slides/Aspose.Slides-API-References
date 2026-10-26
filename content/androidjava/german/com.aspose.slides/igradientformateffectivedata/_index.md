---
title: IGradientFormatEffectiveData
second_title: Aspose.Slides für Android über Java API-Referenz
description: Unveränderliches Objekt, das effektive Gradient-Füllungseigenschaften enthält.
type: docs
url: /de/com.aspose.slides/igradientformateffectivedata/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

Unveränderliches Objekt, das effektive Gradient-Füllungseigenschaften enthält.

--------------------

Dieses Interface wird als Teil von [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) und [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata) verwendet.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Gibt den Drehmodus für einen Gradient zurück. |
| [getGradientDirection()](#getGradientDirection--) | Gibt den Stil eines Gradients zurück. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Gibt den Winkel eines Gradients zurück. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Bestimmt, ob ein Gradient skaliert ist. |
| [getGradientShape()](#getGradientShape--) | Gibt die Form eines Gradients zurück. |
| [getGradientStops()](#getGradientStops--) | Gibt die Sammlung der Gradient-Stops zurück. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```


Gibt den Drehmodus für einen Gradient zurück. Nur lesbar [TileFlip](../../com.aspose.slides/tileflip).

**Rückgabe:**
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```


Gibt den Stil eines Gradients zurück. Nur lesbar [GradientDirection](../../com.aspose.slides/gradientdirection).

**Rückgabe:**
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```


Gibt den Winkel eines Gradients zurück. Nur lesbar float.

**Rückgabe:**
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```


Bestimmt, ob ein Gradient skaliert ist. Nur lesbar boolean.

**Rückgabe:**
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```


Gibt die Form eines Gradients zurück. Nur lesbar [GradientShape](../../com.aspose.slides/gradientshape).

**Rückgabe:**
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```


Gibt die Sammlung der Gradient-Stops zurück. Nur lesbar [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata).

**Rückgabe:**
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)