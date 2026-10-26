---
title: IOuterShadow
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un effetto di ombra esterna.
type: docs
url: /it/com.aspose.slides/ioutershadow/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

Rappresenta un effetto di ombra esterna.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Raggio di sfocatura, in punti. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Raggio di sfocatura, in punti. |
| [getDirection()](#getDirection--) | Direzione dell'ombra, in gradi. |
| [setDirection(float value)](#setDirection-float-) | Direzione dell'ombra, in gradi. |
| [getDistance()](#getDistance--) | Distanza dell'ombra dall'oggetto, in punti. |
| [setDistance(double value)](#setDistance-double-) | Distanza dell'ombra dall'oggetto, in punti. |
| [getShadowColor()](#getShadowColor--) | Colore dell'ombra. |
| [getRectangleAlign()](#getRectangleAlign--) | Allineamento del rettangolo. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Allineamento del rettangolo. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Angolo di inclinazione orizzontale, in gradi. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Angolo di inclinazione orizzontale, in gradi. |
| [getSkewVertical()](#getSkewVertical--) | Angolo di inclinazione verticale, in gradi. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Angolo di inclinazione verticale, in gradi. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Indica se l'ombra ruota insieme alla forma. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Indica se l'ombra ruota insieme alla forma. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Fattore di scala orizzontale, in percentuale della dimensione originale. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Fattore di scala orizzontale, in percentuale della dimensione originale. |
| [getScaleVertical()](#getScaleVertical--) | Fattore di scala verticale, in percentuale della dimensione originale. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Fattore di scala verticale, in percentuale della dimensione originale. |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

Raggio di sfocatura, in punti. Valore predefinito - 0 pt. Lettura/scrittura double.

**Restituisce:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

Raggio di sfocatura, in punti. Valore predefinito - 0 pt. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Direzione dell'ombra, in gradi. Valore predefinito - 0 � (da sinistra a destra). Lettura/scrittura float.

**Restituisce:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Direzione dell'ombra, in gradi. Valore predefinito - 0 � (da sinistra a destra). Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Distanza dell'ombra dall'oggetto, in punti. Valore predefinito - 0 pt. Lettura/scrittura double.

**Restituisce:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Distanza dell'ombra dall'oggetto, in punti. Valore predefinito - 0 pt. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Colore dell'ombra. Valore predefinito - nero automatico (dipendente dal tema). Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

Allineamento del rettangolo. Valore predefinito - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Lettura/scrittura [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Restituisce:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

Allineamento del rettangolo. Valore predefinito - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Lettura/scrittura [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

Angolo di inclinazione orizzontale, in gradi. Valore predefinito - 0 �. Lettura/scrittura double.

**Restituisce:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

Angolo di inclinazione orizzontale, in gradi. Valore predefinito - 0 �. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

Angolo di inclinazione verticale, in gradi. Valore predefinito - 0 �. Lettura/scrittura double.

**Restituisce:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

Angolo di inclinazione verticale, in gradi. Valore predefinito - 0 �. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

Indica se l'ombra ruota insieme alla forma. Valore predefinito - true. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

Indica se l'ombra ruota insieme alla forma. Valore predefinito - true. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

Fattore di scala orizzontale, in percentuale della dimensione originale. La scala negativa provoca un ribaltamento. Valore predefinito - 100 %. Lettura/scrittura double.

**Restituisce:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

Fattore di scala orizzontale, in percentuale della dimensione originale. La scala negativa provoca un ribaltamento. Valore predefinito - 100 %. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

Fattore di scala verticale, in percentuale della dimensione originale. La scala negativa provoca un ribaltamento. Valore predefinito - 100 %. Lettura/scrittura double.

**Restituisce:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

Fattore di scala verticale, in percentuale della dimensione originale. La scala negativa provoca un ribaltamento. Valore predefinito - 100 %. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |