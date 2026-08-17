---
title: IMotionEffect
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente le comportement d'effet de mouvement.
type: docs
url: /fr/com.aspose.slides/imotioneffect/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

Représente le comportement d'un effet de mouvement.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getFrom()](#getFrom--) | Spécifie une coordonnée x/y à partir de laquelle démarrer l'animation (en pourcentage). |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | Spécifie une coordonnée x/y à partir de laquelle démarrer l'animation (en pourcentage). |
| [getTo()](#getTo--) | Spécifie la position cible pour un effet de mouvement d'animation (en pourcentage). |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | Spécifie la position cible pour un effet de mouvement d'animation (en pourcentage). |
| [getBy()](#getBy--) | Décrit la valeur de décalage relative pour l'animation (en pourcentage). |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | Décrit la valeur de décalage relative pour l'animation (en pourcentage). |
| [getRotationCenter()](#getRotationCenter--) | Décrit le centre de rotation utilisé pour faire pivoter un tracé de mouvement d'un angle X. |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | Décrit le centre de rotation utilisé pour faire pivoter un tracé de mouvement d'un angle X. |
| [getOrigin()](#getOrigin--) | Spécifie à quoi l'origine du tracé de mouvement est relative, comme la disposition de la diapositive ou le parent. |
| [setOrigin(int value)](#setOrigin-int-) | Spécifie à quoi l'origine du tracé de mouvement est relative, comme la disposition de la diapositive ou le parent. |
| [getPath()](#getPath--) | Spécifie le primitive de chemin suivi des coordonnées pour le mouvement d'animation. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Spécifie le primitive de chemin suivi des coordonnées pour le mouvement d'animation. |
| [getPathEditMode()](#getPathEditMode--) | Spécifie comment le tracé de mouvement se déplace lorsqu'une forme est déplacée. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Spécifie comment le tracé de mouvement se déplace lorsqu'une forme est déplacée. |
| [getAngle()](#getAngle--) | Décrit l'angle relatif du tracé de mouvement. |
| [setAngle(float value)](#setAngle-float-) | Décrit l'angle relatif du tracé de mouvement. |

### getFrom() {#getFrom--}
```
public abstract Point2D.Float getFrom()
```

Spécifie une coordonnée x/y à partir de laquelle démarrer l'animation (en pourcentage). Lecture/écriture java.awt.geom.Point2D.Float.

**Retour :**
java.awt.geom.Point2D.Float

### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public abstract void setFrom(Point2D.Float value)
```

Spécifie une coordonnée x/y à partir de laquelle démarrer l'animation (en pourcentage). Lecture/écriture java.awt.geom.Point2D.Float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getTo() {#getTo--}
```
public abstract Point2D.Float getTo()
```

Spécifie la position cible pour un effet de mouvement d'animation (en pourcentage). Lecture/écriture java.awt.geom.Point2D.Float.

**Retour :**
java.awt.geom.Point2D.Float

### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public abstract void setTo(Point2D.Float value)
```

Spécifie la position cible pour un effet de mouvement d'animation (en pourcentage). Lecture/écriture java.awt.geom.Point2D.Float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getBy() {#getBy--}
```
public abstract Point2D.Float getBy()
```

Décrit la valeur de décalage relative pour l'animation (en pourcentage). Lecture/écriture java.awt.geom.Point2D.Float.

**Retour :**
java.awt.geom.Point2D.Float

### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public abstract void setBy(Point2D.Float value)
```

Décrit la valeur de décalage relative pour l'animation (en pourcentage). Lecture/écriture java.awt.geom.Point2D.Float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract Point2D.Float getRotationCenter()
```

Décrit le centre de rotation utilisé pour faire pivoter un tracé de mouvement d'un angle X. Lecture/écriture java.awt.geom.Point2D.Float.

**Retour :**
java.awt.geom.Point2D.Float

### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public abstract void setRotationCenter(Point2D.Float value)
```

Décrit le centre de rotation utilisé pour faire pivoter un tracé de mouvement d'un angle X. Lecture/écriture java.awt.geom.Point2D.Float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Spécifie à quoi l'origine du tracé de mouvement est relative, comme la disposition de la diapositive ou le parent. Lecture/écriture [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Retour :**
int

### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

Spécifie à quoi l'origine du tracé de mouvement est relative, comme la disposition de la diapositive ou le parent. Lecture/écriture [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

Spécifie le primitive de chemin suivi des coordonnées pour le mouvement d'animation. Lecture/écriture [IMotionPath](../../com.aspose.slides/imotionpath).

**Retour :**
[IMotionPath](../../com.aspose.slides/imotionpath)

### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

Spécifie le primitive de chemin suivi des coordonnées pour le mouvement d'animation. Lecture/écriture [IMotionPath](../../com.aspose.slides/imotionpath).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

Spécifie comment le tracé de mouvement se déplace lorsqu'une forme est déplacée. Lecture/écriture [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Retour :**
int

### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

Spécifie comment le tracé de mouvement se déplace lorsqu'une forme est déplacée. Lecture/écriture [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

Décrit l'angle relatif du tracé de mouvement. Lecture/écriture float.

**Retour :**
float

### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

Décrit l'angle relatif du tracé de mouvement. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |