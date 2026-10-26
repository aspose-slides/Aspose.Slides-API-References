---
title: IColorEffect
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente un effet de couleur pour un comportement d'animation.
type: docs
url: /fr/com.aspose.slides/icoloreffect/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IColorEffect extends IBehavior
```

Représente un effet de couleur pour un comportement d'animation.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFrom()](#getFrom--) | Cette valeur est utilisée pour spécifier la couleur de départ du comportement. |
| [setFrom(IColorFormat value)](#setFrom-com.aspose.slides.IColorFormat-) | Cette valeur est utilisée pour spécifier la couleur de départ du comportement. |
| [getTo()](#getTo--) | Décrit la couleur résultante pour le changement de couleur de l'animation. |
| [setTo(IColorFormat value)](#setTo-com.aspose.slides.IColorFormat-) | Décrit la couleur résultante pour le changement de couleur de l'animation. |
| [getBy()](#getBy--) | Décrit la valeur de décalage relatif pour l'animation de couleur. |
| [setBy(IColorOffset value)](#setBy-com.aspose.slides.IColorOffset-) | Décrit la valeur de décalage relatif pour l'animation de couleur. |
| [getColorSpace()](#getColorSpace--) | Représente l'espace colorimétrique du comportement. |
| [setColorSpace(int value)](#setColorSpace-int-) | Représente l'espace colorimétrique du comportement. |
| [getDirection()](#getDirection--) | Spécifie la direction dans laquelle faire tourner la teinte autour du cercle chromatique. |
| [setDirection(int value)](#setDirection-int-) | Spécifie la direction dans laquelle faire tourner la teinte autour du cercle chromatique. |

### getFrom() {#getFrom--}
```
public abstract IColorFormat getFrom()
```

Cette valeur est utilisée pour spécifier la couleur de départ du comportement. Lecture/écriture [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)

### setFrom(IColorFormat value) {#setFrom-com.aspose.slides.IColorFormat-}
```
public abstract void setFrom(IColorFormat value)
```

Cette valeur est utilisée pour spécifier la couleur de départ du comportement. Lecture/écriture [IColorFormat](../../com.aspose.slides/icolorformat).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getTo() {#getTo--}
```
public abstract IColorFormat getTo()
```

Décrit la couleur résultante pour le changement de couleur de l'animation. Lecture/écriture [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)

### setTo(IColorFormat value) {#setTo-com.aspose.slides.IColorFormat-}
```
public abstract void setTo(IColorFormat value)
```

Décrit la couleur résultante pour le changement de couleur de l'animation. Lecture/écriture [IColorFormat](../../com.aspose.slides/icolorformat).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getBy() {#getBy--}
```
public abstract IColorOffset getBy()
```

Décrit la valeur de décalage relatif pour l'animation de couleur. Lecture/écriture [IColorOffset](../../com.aspose.slides/icoloroffset).

**Renvoie :**
[IColorOffset](../../com.aspose.slides/icoloroffset)

### setBy(IColorOffset value) {#setBy-com.aspose.slides.IColorOffset-}
```
public abstract void setBy(IColorOffset value)
```

Décrit la valeur de décalage relatif pour l'animation de couleur. Lecture/écriture [IColorOffset](../../com.aspose.slides/icoloroffset).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IColorOffset](../../com.aspose.slides/icoloroffset) |  |

### getColorSpace() {#getColorSpace--}
```
public abstract int getColorSpace()
```

Représente l'espace colorimétrique du comportement. Lecture/écriture [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Renvoie :**
int

### setColorSpace(int value) {#setColorSpace-int-}
```
public abstract void setColorSpace(int value)
```

Représente l'espace colorimétrique du comportement. Lecture/écriture [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Spécifie la direction dans laquelle faire tourner la teinte autour du cercle chromatique. Lecture/écriture [ColorDirection](../../com.aspose.slides/colordirection).

**Renvoie :**
int

### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Spécifie la direction dans laquelle faire tourner la teinte autour du cercle chromatique. Lecture/écriture [ColorDirection](../../com.aspose.slides/colordirection).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |