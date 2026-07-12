---
title: IOuterShadow
second_title: Referencia de API de Aspose.Slides para Android mediante Java
description: Representa un efecto de sombra exterior.
type: docs
url: /es/com.aspose.slides/ioutershadow/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

Representa un efecto de sombra exterior.
## Métodos

| Method | Description |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Radio de desenfoque, en puntos. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Radio de desenfoque, en puntos. |
| [getDirection()](#getDirection--) | Dirección de la sombra, en grados. |
| [setDirection(float value)](#setDirection-float-) | Dirección de la sombra, en grados. |
| [getDistance()](#getDistance--) | Distancia de la sombra al objeto, en puntos. |
| [setDistance(double value)](#setDistance-double-) | Distancia de la sombra al objeto, en puntos. |
| [getShadowColor()](#getShadowColor--) | Color de la sombra. |
| [getRectangleAlign()](#getRectangleAlign--) | Alineación del rectángulo. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Alineación del rectángulo. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Ángulo de sesgo horizontal, en grados. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Ángulo de sesgo horizontal, en grados. |
| [getSkewVertical()](#getSkewVertical--) | Ángulo de sesgo vertical, en grados. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Ángulo de sesgo vertical, en grados. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Indica si la sombra gira junto con la forma. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Indica si la sombra gira junto con la forma. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Factor de escala horizontal, en porcentaje del tamaño original. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Factor de escala horizontal, en porcentaje del tamaño original. |
| [getScaleVertical()](#getScaleVertical--) | Factor de escala vertical, en porcentaje del tamaño original. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Factor de escala vertical, en porcentaje del tamaño original. |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

Radio de desenfoque, en puntos. Valor predeterminado - 0 pt. Lectura/escritura double.

**Devuelve:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

Radio de desenfoque, en puntos. Valor predeterminado - 0 pt. Lectura/escritura double.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Dirección de la sombra, en grados. Valor predeterminado - 0 � (left-to-right). Lectura/escritura float.

**Devuelve:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Dirección de la sombra, en grados. Valor predeterminado - 0 � (left-to-right). Lectura/escritura float.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Distancia de la sombra al objeto, en puntos. Valor predeterminado - 0 pt. Lectura/escritura double.

**Devuelve:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Distancia de la sombra al objeto, en puntos. Valor predeterminado - 0 pt. Lectura/escritura double.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Color de la sombra. Valor predeterminado - negro automático (dependiendo del tema). Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

Alineación del rectángulo. Valor predeterminado - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Lectura/escritura [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Devuelve:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

Alineación del rectángulo. Valor predeterminado - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Lectura/escritura [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

Ángulo de sesgo horizontal, en grados. Valor predeterminado - 0 �. Lectura/escritura double.

**Devuelve:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

Ángulo de sesgo horizontal, en grados. Valor predeterminado - 0 �. Lectura/escritura double.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

Ángulo de sesgo vertical, en grados. Valor predeterminado - 0 �. Lectura/escritura double.

**Devuelve:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

Ángulo de sesgo vertical, en grados. Valor predeterminado - 0 �. Lectura/escritura double.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

Indica si la sombra gira junto con la forma. Valor predeterminado - true. Lectura/escritura boolean.

**Devuelve:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

Indica si la sombra gira junto con la forma. Valor predeterminado - true. Lectura/escritura boolean.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

Factor de escala horizontal, en porcentaje del tamaño original. El escalado negativo provoca una inversión. Valor predeterminado - 100 %. Lectura/escritura double.

**Devuelve:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

Factor de escala horizontal, en porcentaje del tamaño original. El escalado negativo provoca una inversión. Valor predeterminado - 100 %. Lectura/escritura double.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

Factor de escala vertical, en porcentaje del tamaño original. El escalado negativo provoca una inversión. Valor predeterminado - 100 %. Lectura/escritura double.

**Devuelve:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

Factor de escala vertical, en porcentaje del tamaño original. El escalado negativo provoca una inversión. Valor predeterminado - 100 %. Lectura/escritura double.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |