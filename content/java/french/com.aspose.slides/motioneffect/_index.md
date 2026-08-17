---
title: MotionEffect
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente le comportement d'effet de mouvement.
type: docs
url: /fr/com.aspose.slides/motioneffect/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IMotionEffect](../../com.aspose.slides/imotioneffect)
```
public class MotionEffect extends Behavior implements IMotionEffect
```

Représente le comportement d'effet de mouvement d'un effet.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFrom()](#getFrom--) | Spécifie une coordonnée x/y à partir de laquelle démarrer l'animation (en pourcentage). |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | Spécifie une coordonnée x/y à partir de laquelle démarrer l'animation (en pourcentage). |
| [getTo()](#getTo--) | Spécifie l'emplacement cible d'un effet de mouvement d'animation (en pourcentage). |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | Spécifie l'emplacement cible d'un effet de mouvement d'animation (en pourcentage). |
| [getBy()](#getBy--) | Décrit la valeur de décalage relative pour l'animation (en pourcentage). |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | Décrit la valeur de décalage relative pour l'animation (en pourcentage). |
| [getRotationCenter()](#getRotationCenter--) | Décrit le centre de rotation utilisé pour faire pivoter un chemin de mouvement d'un angle X. |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | Décrit le centre de rotation utilisé pour faire pivoter un chemin de mouvement d'un angle X. |
| [getOrigin()](#getOrigin--) | Spécifie à quoi l'origine du chemin de mouvement est relative, par exemple la disposition de la diapositive ou le parent. |
| [setOrigin(int value)](#setOrigin-int-) | Spécifie à quoi l'origine du chemin de mouvement est relative, par exemple la disposition de la diapositive ou le parent. |
| [getPath()](#getPath--) | Spécifie le primitive du chemin suivi des coordonnées pour le mouvement d'animation. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Spécifie le primitive du chemin suivi des coordonnées pour le mouvement d'animation. |
| [getPathEditMode()](#getPathEditMode--) | Spécifie comment le chemin de mouvement se déplace lorsqu'une forme est déplacée. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Spécifie comment le chemin de mouvement se déplace lorsqu'une forme est déplacée. |
| [getAngle()](#getAngle--) | Décrit l'angle relatif du chemin de mouvement. |
| [setAngle(float value)](#setAngle-float-) | Décrit l'angle relatif du chemin de mouvement. |
### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```


### getFrom() {#getFrom--}
```
public final Point2D.Float getFrom()
```


Spécifie une coordonnée x/y à partir de laquelle démarrer l'animation (en pourcentage). Lecture/écriture java.awt.geom.Point2D.Float.

**Renvoie:**
java.awt.geom.Point2D.Float
### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public final void setFrom(Point2D.Float value)
```


Spécifie une coordonnée x/y à partir de laquelle démarrer l'animation (en pourcentage). Lecture/écriture java.awt.geom.Point2D.Float.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getTo() {#getTo--}
```
public final Point2D.Float getTo()
```


Spécifie l'emplacement cible d'un effet de mouvement d'animation (en pourcentage). Lecture/écriture java.awt.geom.Point2D.Float.

**Renvoie:**
java.awt.geom.Point2D.Float
### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public final void setTo(Point2D.Float value)
```


Spécifie l'emplacement cible d'un effet de mouvement d'animation (en pourcentage). Lecture/écriture java.awt.geom.Point2D.Float.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getBy() {#getBy--}
```
public final Point2D.Float getBy()
```


Décrit la valeur de décalage relative pour l'animation (en pourcentage). Lecture/écriture java.awt.geom.Point2D.Float.

**Renvoie:**
java.awt.geom.Point2D.Float
### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public final void setBy(Point2D.Float value)
```


Décrit la valeur de décalage relative pour l'animation (en pourcentage). Lecture/écriture java.awt.geom.Point2D.Float.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getRotationCenter() {#getRotationCenter--}
```
public final Point2D.Float getRotationCenter()
```


Décrit le centre de rotation utilisé pour faire pivoter un chemin de mouvement d'un angle X. Lecture/écriture java.awt.geom.Point2D.Float.

**Renvoie:**
java.awt.geom.Point2D.Float
### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public final void setRotationCenter(Point2D.Float value)
```


Décrit le centre de rotation utilisé pour faire pivoter un chemin de mouvement d'un angle X. Lecture/écriture java.awt.geom.Point2D.Float.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```


Spécifie à quoi l'origine du chemin de mouvement est relative, par exemple la disposition de la diapositive ou le parent. Lecture/écriture [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Renvoie:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```


Spécifie à quoi l'origine du chemin de mouvement est relative, par exemple la disposition de la diapositive ou le parent. Lecture/écriture [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```


Spécifie le primitive du chemin suivi des coordonnées pour le mouvement d'animation. Lecture/écriture [IMotionPath](../../com.aspose.slides/imotionpath).

**Renvoie:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```


Spécifie le primitive du chemin suivi des coordonnées pour le mouvement d'animation. Lecture/écriture [IMotionPath](../../com.aspose.slides/imotionpath).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```


Spécifie comment le chemin de mouvement se déplace lorsqu'une forme est déplacée. Lecture/écriture [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Renvoie:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```


Spécifie comment le chemin de mouvement se déplace lorsqu'une forme est déplacée. Lecture/écriture [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```


Décrit l'angle relatif du chemin de mouvement. Lecture/écriture float.

**Renvoie:**
float
### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```


Décrit l'angle relatif du chemin de mouvement. Lecture/écriture float.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |