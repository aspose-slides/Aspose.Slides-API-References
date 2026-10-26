---
title: IGradientStop
second_title: Aspose.Slides for Java API Reference
description: Représente un format de dégradé.
type: docs
url: /fr/com.aspose.slides/igradientstop/
---```
public interface IGradientStop
```

Représente un format de dégradé.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPosition()](#getPosition--) | Renvoie ou définit la position (0..1) d'un arrêt de dégradé. |
| [setPosition(float value)](#setPosition-float-) | Renvoie ou définit la position (0..1) d'un arrêt de dégradé. |
| [getColor()](#getColor--) | Renvoie la couleur d'un arrêt de dégradé. |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```


Renvoie ou définit la position (0..1) d'un arrêt de dégradé. Lecture/écriture float.

**Renvoie :**  
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

**Renvoie :**  
[IColorFormat](../../com.aspose.slides/icolorformat)