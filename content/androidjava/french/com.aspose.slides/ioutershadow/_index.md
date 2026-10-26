---
title: IOuterShadow
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente un effet d'ombre externe.
type: docs
url: /fr/com.aspose.slides/ioutershadow/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

Représente un effet d'ombre externe.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Rayon du flou, en points. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Rayon du flou, en points. |
| [getDirection()](#getDirection--) | Direction de l'ombre, en degrés. |
| [setDirection(float value)](#setDirection-float-) | Direction de l'ombre, en degrés. |
| [getDistance()](#getDistance--) | Distance de l'ombre à l'objet, en points. |
| [setDistance(double value)](#setDistance-double-) | Distance de l'ombre à l'objet, en points. |
| [getShadowColor()](#getShadowColor--) | Couleur de l'ombre. |
| [getRectangleAlign()](#getRectangleAlign--) | Alignement du rectangle. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Alignement du rectangle. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Angle d'inclinaison horizontal, en degrés. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Angle d'inclinaison horizontal, en degrés. |
| [getSkewVertical()](#getSkewVertical--) | Angle d'inclinaison vertical, en degrés. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Angle d'inclinaison vertical, en degrés. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Indique si l'ombre tourne avec la forme. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Indique si l'ombre tourne avec la forme. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Facteur d'échelle horizontal, en pourcentage de la taille originale. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Facteur d'échelle horizontal, en pourcentage de la taille originale. |
| [getScaleVertical()](#getScaleVertical--) | Facteur d'échelle vertical, en pourcentage de la taille originale. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Facteur d'échelle vertical, en pourcentage de la taille originale. |

### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

Rayon du flou, en points. Valeur par défaut - 0 pt. Lecture/écriture double.

**Retourne :**
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

Rayon du flou, en points. Valeur par défaut - 0 pt. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Direction de l'ombre, en degrés. Valeur par défaut - 0 � (de gauche à droite). Lecture/écriture float.

**Retourne :**
float

### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Direction de l'ombre, en degrés. Valeur par défaut - 0 � (de gauche à droite). Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Distance de l'ombre à l'objet, en points. Valeur par défaut - 0 pt. Lecture/écriture double.

**Retourne :**
double

### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Distance de l'ombre à l'objet, en points. Valeur par défaut - 0 pt. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Couleur de l'ombre. Valeur par défaut - black automatique (dépendant du thème). Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Retourne :**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

Alignement du rectangle. Valeur par défaut - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Lecture/écriture [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Retourne :**
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

Alignement du rectangle. Valeur par défaut - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Lecture/écriture [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

Angle d'inclinaison horizontal, en degrés. Valeur par défaut - 0 �. Lecture/écriture double.

**Retourne :**
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

Angle d'inclinaison horizontal, en degrés. Valeur par défaut - 0 �. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

Angle d'inclinaison vertical, en degrés. Valeur par défaut - 0 �. Lecture/écriture double.

**Retourne :**
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

Angle d'inclinaison vertical, en degrés. Valeur par défaut - 0 �. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

Indique si l'ombre tourne avec la forme. Valeur par défaut - true. Lecture/écriture booléen.

**Retourne :**
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

Indique si l'ombre tourne avec la forme. Valeur par défaut - true. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

Facteur d'échelle horizontal, en pourcentage de la taille originale. Une mise à l'échelle négative provoque un retournement. Valeur par défaut - 100 %. Lecture/écriture double.

**Retourne :**
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

Facteur d'échelle horizontal, en pourcentage de la taille originale. Une mise à l'échelle négative provoque un retournement. Valeur par défaut - 100 %. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

Facteur d'échelle vertical, en pourcentage de la taille originale. Une mise à l'échelle négative provoque un retournement. Valeur par défaut - 100 %. Lecture/écriture double.

**Retourne :**
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

Facteur d'échelle vertical, en pourcentage de la taille originale. Une mise à l'échelle négative provoque un retournement. Valeur par défaut - 100 %. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |