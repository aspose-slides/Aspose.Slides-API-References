---
title: IGradientFormat
second_title: Référence de l'API Java d'Aspose.Slides pour Android
description: Représente un format de dégradé.
type: docs
url: /fr/com.aspose.slides/igradientformat/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormat extends IFillParamSource
```

Représente un format de dégradé.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Renvoie ou définit le mode de retournement d'un dégradé. |
| [setTileFlip(int value)](#setTileFlip-int-) | Renvoie ou définit le mode de retournement d'un dégradé. |
| [getGradientDirection()](#getGradientDirection--) | Renvoie ou définit le style d'un dégradé. |
| [setGradientDirection(int value)](#setGradientDirection-int-) | Renvoie ou définit le style d'un dégradé. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Renvoie ou définit l'angle d'un dégradé. |
| [setLinearGradientAngle(float value)](#setLinearGradientAngle-float-) | Renvoie ou définit l'angle d'un dégradé. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Détermine si un dégradé est mis à l'échelle. |
| [setLinearGradientScaled(byte value)](#setLinearGradientScaled-byte-) | Détermine si un dégradé est mis à l'échelle. |
| [getGradientShape()](#getGradientShape--) | Renvoie ou définit la forme d'un dégradé. |
| [setGradientShape(byte value)](#setGradientShape-byte-) | Renvoie ou définit la forme d'un dégradé. |
| [getGradientStops()](#getGradientStops--) | Renvoie la collection des points d'arrêt du dégradé. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

Renvoie ou définit le mode de retournement d'un dégradé. Lecture/écriture [TileFlip](../../com.aspose.slides/tileflip).

**Renvoie :**
int
### setTileFlip(int value) {#setTileFlip-int-}
```
public abstract void setTileFlip(int value)
```

Renvoie ou définit le mode de retournement d'un dégradé. Lecture/écriture [TileFlip](../../com.aspose.slides/tileflip).

Paramètres :
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

Renvoie ou définit le style d'un dégradé. Lecture/écriture [GradientDirection](../../com.aspose.slides/gradientdirection).

**Renvoie :**
int
### setGradientDirection(int value) {#setGradientDirection-int-}
```
public abstract void setGradientDirection(int value)
```

Renvoie ou définit le style d'un dégradé. Lecture/écriture [GradientDirection](../../com.aspose.slides/gradientdirection).

Paramètres :
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

Renvoie ou définit l'angle d'un dégradé. Lecture/écriture float.

**Renvoie :**
float
### setLinearGradientAngle(float value) {#setLinearGradientAngle-float-}
```
public abstract void setLinearGradientAngle(float value)
```

Renvoie ou définit l'angle d'un dégradé. Lecture/écriture float.

Paramètres :
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract byte getLinearGradientScaled()
```

Détermine si un dégradé est mis à l'échelle. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte
### setLinearGradientScaled(byte value) {#setLinearGradientScaled-byte-}
```
public abstract void setLinearGradientScaled(byte value)
```

Détermine si un dégradé est mis à l'échelle. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

Paramètres :
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```

Renvoie ou définit la forme d'un dégradé. Lecture/écriture [GradientShape](../../com.aspose.slides/gradientshape).

**Renvoie :**
byte
### setGradientShape(byte value) {#setGradientShape-byte-}
```
public abstract void setGradientShape(byte value)
```

Renvoie ou définit la forme d'un dégradé. Lecture/écriture [GradientShape](../../com.aspose.slides/gradientshape).

Paramètres :
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollection getGradientStops()
```

Renvoie la collection des points d'arrêt du dégradé. Lecture seule [IGradientStopCollection](../../com.aspose.slides/igradientstopcollection).

**Renvoie :**
[IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)