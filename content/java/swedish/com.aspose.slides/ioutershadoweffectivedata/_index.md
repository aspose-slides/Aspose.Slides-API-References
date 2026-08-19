---
title: IOuterShadowEffectiveData
second_title: Aspose.Slides för Java API-referens
description: Oföränderligt objekt som representerar en yttre skuggeffekt.
type: docs
url: /sv/com.aspose.slides/ioutershadoweffectivedata/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IOuterShadowEffectiveData extends IEffectEffectiveData
```

Oföränderligt objekt som representerar en yttre skuggeffekt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Oskärpe radie. |
| [getDirection()](#getDirection--) | Skuggans riktning. |
| [getDistance()](#getDistance--) | Skuggans avstånd. |
| [getShadowColor()](#getShadowColor--) | Skuggans färg. |
| [getRectangleAlign()](#getRectangleAlign--) | Rektangeljustering. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Anger den horisontella skevhetsvinkeln (i grader). |
| [getSkewVertical()](#getSkewVertical--) | Anger den vertikala skevhetsvinkeln (i grader). |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Anger om skuggan ska rotera med formen om formen roteras. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Anger den horisontella skalningsfaktorn, negativ skalning orsakar en vändning. |
| [getScaleVertical()](#getScaleVertical--) | Anger den vertikala skalningsfaktorn, negativ skalning orsakar en vändning. |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

Blur radius. Skrivskyddad double.

**Returnerar:**
double
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Direction of shadow. Skrivskyddad float.

**Returnerar:**
float
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Distance of shadow. Skrivskyddad double.

**Returnerar:**
double
### getShadowColor() {#getShadowColor--}
```
public abstract Color getShadowColor()
```

Color of shadow. Skrivskyddad java.awt.Color.

**Returnerar:**
java.awt.Color
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

Rectangle alignment. Skrivskyddad [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Returnerar:**
byte
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

Specifies the horizontal skew angle (in degrees). Skrivskyddad double.

**Returnerar:**
double
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

Specifies the vertical skew angle (in degrees). Skrivskyddad double.

**Returnerar:**
double
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

Specifies whether the shadow should rotate with the shape if the shape is rotated. Skrivskyddad boolean.

**Returnerar:**
boolean
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

Specifies the horizontal scaling factor, negative scaling causes a flip. Skrivskyddad double.

**Returnerar:**
double
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

Specifies the vertical scaling factor, negative scaling causes a flip. Skrivskyddad double.

**Returnerar:**
double