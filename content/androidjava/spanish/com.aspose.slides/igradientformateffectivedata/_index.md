---
title: IGradientFormatEffectiveData
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Objeto inmutable que contiene propiedades efectivas de relleno de degradado.
type: docs
url: /es/com.aspose.slides/igradientformateffectivedata/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

Objeto inmutable que contiene propiedades efectivas de relleno de degradado.

--------------------

Esta interfaz se usa como parte de [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) y [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Métodos

| Método | Descripción |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Devuelve el modo de volteo de un degradado. |
| [getGradientDirection()](#getGradientDirection--) | Devuelve el estilo de un degradado. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Devuelve el ángulo de un degradado. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Determina si un degradado está escalado. |
| [getGradientShape()](#getGradientShape--) | Devuelve la forma de un degradado. |
| [getGradientStops()](#getGradientStops--) | Devuelve la colección de puntos de parada del degradado. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```


Devuelve el modo de volteo de un degradado. Solo lectura [TileFlip](../../com.aspose.slides/tileflip).

**Devuelve:**
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```


Devuelve el estilo de un degradado. Solo lectura [GradientDirection](../../com.aspose.slides/gradientdirection).

**Devuelve:**
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```


Devuelve el ángulo de un degradado. Solo lectura float.

**Devuelve:**
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```


Determina si un degradado está escalado. Solo lectura boolean.

**Devuelve:**
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```


Devuelve la forma de un degradado. Solo lectura [GradientShape](../../com.aspose.slides/gradientshape).

**Devuelve:**
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```


Devuelve la colección de puntos de parada del degradado. Solo lectura [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata).

**Devuelve:**
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)