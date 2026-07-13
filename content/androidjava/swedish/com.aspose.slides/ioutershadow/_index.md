---
title: IOuterShadow
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en yttre skuggeffekt.
type: docs
url: /sv/com.aspose.slides/ioutershadow/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

Representerar en yttre skuggeffekt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Blur radius, i punkter. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Blur radius, i punkter. |
| [getDirection()](#getDirection--) | Riktning för skuggan, i grader. |
| [setDirection(float value)](#setDirection-float-) | Riktning för skuggan, i grader. |
| [getDistance()](#getDistance--) | Avståndet för skuggan från objektet, i punkter. |
| [setDistance(double value)](#setDistance-double-) | Avståndet för skuggan från objektet, i punkter. |
| [getShadowColor()](#getShadowColor--) | Färg på skuggan. |
| [getRectangleAlign()](#getRectangleAlign--) | Rektangeljustering. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Rektangeljustering. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Horisontell skevvinkel, i grader. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Horisontell skevvinkel, i grader. |
| [getSkewVertical()](#getSkewVertical--) | Vertikal skevvinkel, i grader. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Vertikal skevvinkel, i grader. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Indikerar om skuggan roterar tillsammans med formen. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Indikerar om skuggan roterar tillsammans med formen. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Horisontell skalningsfaktor, i procent av originalstorleken. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Horisontell skalningsfaktor, i procent av originalstorleken. |
| [getScaleVertical()](#getScaleVertical--) | Vertikal skalningsfaktor, i procent av originalstorleken. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Vertikal skalningsfaktor, i procent av originalstorleken. |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```


Blur radius, i punkter. Standardvärde - 0 pt. Läs/skriv double.

**Returnerar:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```


Blur radius, i punkter. Standardvärde - 0 pt. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


Riktning för skuggan, i grader. Standardvärde - 0 � (vänster till höger). Läs/skriv float.

**Returnerar:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```


Riktning för skuggan, i grader. Standardvärde - 0 � (vänster till höger). Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


Avståndet för skuggan från objektet, i punkter. Standardvärde - 0 pt. Läs/skriv double.

**Returnerar:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```


Avståndet för skuggan från objektet, i punkter. Standardvärde - 0 pt. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```


Färg på skuggan. Standardvärde - automatisk svart (tema-beroende). Endast läsning [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```


Rektangeljustering. Standardvärde - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Läs/skriv [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Returnerar:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```


Rektangeljustering. Standardvärde - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Läs/skriv [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```


Horisontell skevvinkel, i grader. Standardvärde - 0 �. Läs/skriv double.

**Returnerar:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```


Horisontell skevvinkel, i grader. Standardvärde - 0 �. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```


Vertikal skevvinkel, i grader. Standardvärde - 0 �. Läs/skriv double.

**Returnerar:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```


Vertikal skevvinkel, i grader. Standardvärde - 0 �. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```


Indikerar om skuggan roterar tillsammans med formen. Standardvärde - true. Läs/skriv boolean.

**Returnerar:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```


Indikerar om skuggan roterar tillsammans med formen. Standardvärde - true. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```


Horisontell skalningsfaktor, i procent av originalstorleken. Negativ skalning ger en spegling. Standardvärde - 100 %. Läs/skriv double.

**Returnerar:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```


Horisontell skalningsfaktor, i procent av originalstorleken. Negativ skalning ger en spegling. Standardvärde - 100 %. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```


Vertikal skalningsfaktor, i procent av originalstorleken. Negativ skalning ger en spegling. Standardvärde - 100 %. Läs/skriv double.

**Returnerar:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```


Vertikal skalningsfaktor, i procent av originalstorleken. Negativ skalning ger en spegling. Standardvärde - 100 %. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |