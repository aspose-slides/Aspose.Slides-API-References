---
title: IGradientFormatEffectiveData
second_title: Aspose.Slides para Android via Referência da API Java
description: Objeto imutável que contém propriedades efetivas de preenchimento de gradiente.
type: docs
url: /pt/com.aspose.slides/igradientformateffectivedata/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

Objeto Imutável que contém propriedades efetivas de preenchimento de gradiente.

--------------------

Esta interface é usada como parte de [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) e [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Métodos

| Método | Descrição |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Retorna o modo de inversão para um gradiente. |
| [getGradientDirection()](#getGradientDirection--) | Retorna o estilo de um gradiente. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Retorna o ângulo de um gradiente. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Determina se um gradiente está dimensionado. |
| [getGradientShape()](#getGradientShape--) | Retorna a forma de um gradiente. |
| [getGradientStops()](#getGradientStops--) | Retorna a coleção de pontos de parada do gradiente. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

Retorna o modo de inversão para um gradiente. Somente leitura [TileFlip](../../com.aspose.slides/tileflip).

**Retorna:**
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

Retorna o estilo de um gradiente. Somente leitura [GradientDirection](../../com.aspose.slides/gradientdirection).

**Retorna:**
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

Retorna o ângulo de um gradiente. Somente leitura float.

**Retorna:**
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```

Determina se um gradiente está dimensionado. Somente leitura boolean.

**Retorna:**
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```

Retorna a forma de um gradiente. Somente leitura [GradientShape](../../com.aspose.slides/gradientshape).

**Retorna:**
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```

Retorna a coleção de pontos de parada do gradiente. Somente leitura [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata).

**Retorna:**
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)