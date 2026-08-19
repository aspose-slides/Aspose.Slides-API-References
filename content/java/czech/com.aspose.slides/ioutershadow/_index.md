---
title: IOuterShadow
second_title: Aspose.Slides pro Java - referenční příručka
description: Reprezentuje efekt vnějšího stínu.
type: docs
url: /cs/com.aspose.slides/ioutershadow/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

Reprezentuje efekt vnějšího stínu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Poloměr rozostření v bodech. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Poloměr rozostření v bodech. |
| [getDirection()](#getDirection--) | Směr stínu ve stupních. |
| [setDirection(float value)](#setDirection-float-) | Směr stínu ve stupních. |
| [getDistance()](#getDistance--) | Vzdálenost stínu od objektu v bodech. |
| [setDistance(double value)](#setDistance-double-) | Vzdálenost stínu od objektu v bodech. |
| [getShadowColor()](#getShadowColor--) | Barva stínu. |
| [getRectangleAlign()](#getRectangleAlign--) | Zarovnání obdélníku. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Zarovnání obdélníku. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Úhel vodorovného zkosení ve stupních. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Úhel vodorovného zkosení ve stupních. |
| [getSkewVertical()](#getSkewVertical--) | Úhel svislého zkosení ve stupních. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Úhel svislého zkosení ve stupních. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Určuje, zda se stín otáčí spolu s tvarem. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Určuje, zda se stín otáčí spolu s tvarem. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Faktor vodorovného měřítka v procentech původní velikosti. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Faktor vodorovného měřítka v procentech původní velikosti. |
| [getScaleVertical()](#getScaleVertical--) | Faktor svislého měřítka v procentech původní velikosti. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Faktor svislého měřítka v procentech původní velikosti. |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```


Poloměr rozostření v bodech. Výchozí hodnota – 0 pt. Čtení/zápis double.

**Vrací:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```


Poloměr rozostření v bodech. Výchozí hodnota – 0 pt. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


Směr stínu ve stupních. Výchozí hodnota – 0 � (zleva doprava). Čtení/zápis float.

**Vrací:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```


Směr stínu ve stupních. Výchozí hodnota – 0 � (zleva doprava). Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


Vzdálenost stínu od objektu v bodech. Výchozí hodnota – 0 pt. Čtení/zápis double.

**Vrací:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```


Vzdálenost stínu od objektu v bodech. Výchozí hodnota – 0 pt. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```


Barva stínu. Výchozí hodnota – automatická černá (závisí na motivu). Pouze ke čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```


Zarovnání obdélníku. Výchozí hodnota – [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Čtení/zápis [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Vrací:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```


Zarovnání obdélníku. Výchozí hodnota – [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Čtení/zápis [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```


Úhel vodorovného zkosení ve stupních. Výchozí hodnota – 0 �. Čtení/zápis double.

**Vrací:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```


Úhel vodorovného zkosení ve stupních. Výchozí hodnota – 0 �. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```


Úhel svislého zkosení ve stupních. Výchozí hodnota – 0 �. Čtení/zápis double.

**Vrací:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```


Úhel svislého zkosení ve stupních. Výchozí hodnota – 0 �. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```


Určuje, zda se stín otáčí spolu s tvarem. Výchozí hodnota – true. Čtení/zápis boolean.

**Vrací:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```


Určuje, zda se stín otáčí spolu s tvarem. Výchozí hodnota – true. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```


Faktor vodorovného měřítka v procentech původní velikosti. Negativní měřítko způsobí převrácení. Výchozí hodnota – 100 %. Čtení/zápis double.

**Vrací:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```


Faktor vodorovného měřítka v procentech původní velikosti. Negativní měřítko způsobí převrácení. Výchozí hodnota – 100 %. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```


Faktor svislého měřítka v procentech původní velikosti. Negativní měřítko způsobí převrácení. Výchozí hodnota – 100 %. Čtení/zápis double.

**Vrací:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```


Faktor svislého měřítka v procentech původní velikosti. Negativní měřítko způsobí převrácení. Výchozí hodnota – 100 %. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |