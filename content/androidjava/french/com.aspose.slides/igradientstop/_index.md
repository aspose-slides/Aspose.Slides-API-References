---
title: IGradientStop
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a gradient format.
type: docs
url: /fr/com.aspose.slides/igradientstop/
---```
public interface IGradientStop
```

Représente un format de dégradé.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPosition()](#getPosition--) | Returns or sets the position (0..1) of a gradient stop. |
| [setPosition(float value)](#setPosition-float-) | Returns or sets the position (0..1) of a gradient stop. |
| [getColor()](#getColor--) | Returns the color of a gradient stop. |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

Renvoie ou définit la position (0..1) d'un arrêt de dégradé. Lecture/écriture float.

**Retour :**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

Renvoie ou définit la position (0..1) d'un arrêt de dégradé. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Renvoie la couleur d'un arrêt de dégradé. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour :**
[IColorFormat](../../com.aspose.slides/icolorformat)