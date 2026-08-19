---
title: IOuterShadow
second_title: Aspose.Slides voor Java API Referentie
description: Stelt een Outer Shadow-effect voor.
type: docs
url: /nl/com.aspose.slides/ioutershadow/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

Stelt een Outer Shadow-effect voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Blur radius, in punten. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Blur radius, in punten. |
| [getDirection()](#getDirection--) | Richting van de schaduw, in graden. |
| [setDirection(float value)](#setDirection-float-) | Richting van de schaduw, in graden. |
| [getDistance()](#getDistance--) | Afstand van de schaduw tot het object, in punten. |
| [setDistance(double value)](#setDistance-double-) | Afstand van de schaduw tot het object, in punten. |
| [getShadowColor()](#getShadowColor--) | Kleur van de schaduw. |
| [getRectangleAlign()](#getRectangleAlign--) | Rechthoekuitlijning. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Rechthoekuitlijning. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Horizontale scheefhoek, in graden. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Horizontale scheefhoek, in graden. |
| [getSkewVertical()](#getSkewVertical--) | Verticale scheefhoek, in graden. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Verticale scheefhoek, in graden. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Geeft aan of de schaduw meedraait met de vorm. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Geeft aan of de schaduw meedraait met de vorm. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Horizontale schaalfactor, in procenten van de originele grootte. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Horizontale schaalfactor, in procenten van de originele grootte. |
| [getScaleVertical()](#getScaleVertical--) | Verticale schaalfactor, in procenten van de originele grootte. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Verticale schaalfactor, in procenten van de originele grootte. |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

Blur radius, in punten. Standaardwaarde - 0 pt. Lezen/Schrijven double.

**Retour:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

Blur radius, in punten. Standaardwaarde - 0 pt. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Richting van de schaduw, in graden. Standaardwaarde - 0 � (van links naar rechts). Lezen/Schrijven float.

**Retour:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Richting van de schaduw, in graden. Standaardwaarde - 0 � (van links naar rechts). Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Afstand van de schaduw tot het object, in punten. Standaardwaarde - 0 pt. Lezen/Schrijven double.

**Retour:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Afstand van de schaduw tot het object, in punten. Standaardwaarde - 0 pt. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Kleur van de schaduw. Standaardwaarde - automatisch zwart (themavariant). Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

Rechthoekuitlijning. Standaardwaarde - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Lezen/Schrijven [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Retour:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

Rechthoekuitlijning. Standaardwaarde - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Lezen/Schrijven [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

Horizontale scheefhoek, in graden. Standaardwaarde - 0 �. Lezen/Schrijven double.

**Retour:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

Horizontale scheefhoek, in graden. Standaardwaarde - 0 �. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

Verticale scheefhoek, in graden. Standaardwaarde - 0 �. Lezen/Schrijven double.

**Retour:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

Verticale scheefhoek, in graden. Standaardwaarde - 0 �. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

Geeft aan of de schaduw meedraait met de vorm. Standaardwaarde - true. Lezen/Schrijven boolean.

**Retour:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

Geeft aan of de schaduw meedraait met de vorm. Standaardwaarde - true. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

Horizontale schaalfactor, in procenten van de originele grootte. Negatieve schaal veroorzaakt een omkering. Standaardwaarde - 100 %. Lezen/Schrijven double.

**Retour:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

Horizontale schaalfactor, in procenten van de originele grootte. Negatieve schaal veroorzaakt een omkering. Standaardwaarde - 100 %. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

Verticale schaalfactor, in procenten van de originele grootte. Negatieve schaal veroorzaakt een omkering. Standaardwaarde - 100 %. Lezen/Schrijven double.

**Retour:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

Verticale schaalfactor, in procenten van de originele grootte. Negatieve schaal veroorzaakt een omkering. Standaardwaarde - 100 %. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |