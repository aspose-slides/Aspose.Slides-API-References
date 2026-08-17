---
title: IGradientFormatEffectiveData
second_title: Aspose.Slides für Java API-Referenz
description: Unveränderliches Objekt, das effektive Gradientfüllungseigenschaften enthält.
type: docs
url: /de/com.aspose.slides/igradientformateffectivedata/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

Unveränderliches Objekt, das effektive Gradientfüllungseigenschaften enthält.

--------------------

Diese Schnittstelle wird als Teil von [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) und [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Gibt den Kippmodus eines Gradienten zurück. |
| [getGradientDirection()](#getGradientDirection--) | Gibt den Stil eines Gradienten zurück. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Gibt den Winkel eines Gradienten zurück. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Bestimmt, ob ein Gradient skaliert ist. |
| [getGradientShape()](#getGradientShape--) | Gibt die Form eines Gradienten zurück. |
| [getGradientStops()](#getGradientStops--) | Gibt die Sammlung der Gradient-Stopps zurück. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

Gibt den Kippmodus eines Gradienten zurück. Nur lesbar [TileFlip](../../com.aspose.slides/tileflip).

**Rückgabe:**
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

Gibt den Stil eines Gradienten zurück. Nur lesbar [GradientDirection](../../com.aspose.slides/gradientdirection).

**Rückgabe:**
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

Gibt den Winkel eines Gradienten zurück. Nur lesbar float.

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

Gibt die Form eines Gradienten zurück. Nur lesbar [GradientShape](../../com.aspose.slides/gradientshape).

**Rückgabe:**
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```

Gibt die Sammlung der Gradient-Stopps zurück. Nur lesbar [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata).

**Rückgabe:**
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)