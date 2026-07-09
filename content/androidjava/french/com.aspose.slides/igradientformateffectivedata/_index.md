---
title: IGradientFormatEffectiveData
second_title: Référence de l'API Java d'Aspose.Slides pour Android
description: Objet immuable contenant les propriétés effectives de remplissage de dégradé.
type: docs
url: /fr/com.aspose.slides/igradientformateffectivedata/
---
**Toutes les interfaces implémentées:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

Objet immuable contenant les propriétés de remplissage de dégradé effectives.

--------------------

Cette interface est utilisée comme partie de [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) et [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Renvoie le mode de retournement pour un dégradé. |
| [getGradientDirection()](#getGradientDirection--) | Renvoie le style d'un dégradé. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Renvoie l'angle d'un dégradé. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Détermine si un dégradé est mis à l'échelle. |
| [getGradientShape()](#getGradientShape--) | Renvoie la forme d'un dégradé. |
| [getGradientStops()](#getGradientStops--) | Renvoie la collection des arrêts de dégradé. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```


Renvoie le mode de retournement pour un dégradé. Lecture seule [TileFlip](../../com.aspose.slides/tileflip).

**Renvoie:** 
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```


Renvoie le style d'un dégradé. Lecture seule [GradientDirection](../../com.aspose.slides/gradientdirection).

**Renvoie:** 
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```


Renvoie l'angle d'un dégradé. Lecture seule float.

**Renvoie:** 
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```


Détermine si un dégradé est mis à l'échelle. Lecture seule boolean.

**Renvoie:** 
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```


Renvoie la forme d'un dégradé. Lecture seule [GradientShape](../../com.aspose.slides/gradientshape).

**Renvoie:** 
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```


Renvoie la collection des arrêts de dégradé. Lecture seule [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata).

**Renvoie:** 
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)