---
title: IMotionEffect
second_title: Aspose.Slides pour Android via la référence d'API Java
description: Représente le comportement de l'effet de mouvement.
type: docs
url: /fr/com.aspose.slides/imotioneffect/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

Représente le comportement de l'effet de mouvement.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFrom()](#getFrom--) | Spécifie une coordonnée x/y à partir de laquelle démarrer l'animation (en pourcentage). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Spécifie une coordonnée x/y à partir de laquelle démarrer l'animation (en pourcentage). |
| [getTo()](#getTo--) | Spécifie l'emplacement cible d'un effet de mouvement d'animation (en pourcentage). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Spécifie l'emplacement cible d'un effet de mouvement d'animation (en pourcentage). |
| [getBy()](#getBy--) | Décrit la valeur de décalage relative de l'animation (en pourcentage). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Décrit la valeur de décalage relative de l'animation (en pourcentage). |
| [getRotationCenter()](#getRotationCenter--) | Décrit le centre de rotation utilisé pour faire pivoter un chemin de mouvement d'un angle X. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Décrit le centre de rotation utilisé pour faire pivoter un chemin de mouvement d'un angle X. |
| [getOrigin()](#getOrigin--) | Spécifie à quoi l'origine du chemin de mouvement est relative, comme la disposition de la diapositive ou le parent. |
| [setOrigin(int value)](#setOrigin-int-) | Spécifie à quoi l'origine du chemin de mouvement est relative, comme la disposition de la diapositive ou le parent. |
| [getPath()](#getPath--) | Spécifie la primitive de chemin suivie des coordonnées pour le mouvement d'animation. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Spécifie la primitive de chemin suivie des coordonnées pour le mouvement d'animation. |
| [getPathEditMode()](#getPathEditMode--) | Spécifie comment le chemin de mouvement se déplace lorsque la forme est déplacée. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Spécifie comment le chemin de mouvement se déplace lorsque la forme est déplacée. |
| [getAngle()](#getAngle--) | Décrit l'angle relatif du chemin de mouvement. |
| [setAngle(float value)](#setAngle-float-) | Décrit l'angle relatif du chemin de mouvement. |

### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```

Spécifie une coordonnée x/y à partir de laquelle démarrer l'animation (en pourcentage). Lecture/écriture android.graphics.PointF.

**Renvoie :**
android.graphics.PointF

### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```

Spécifie une coordonnée x/y à partir de laquelle démarrer l'animation (en pourcentage).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public abstract PointF getTo()
```

Spécifie l'emplacement cible d'un effet de mouvement d'animation (en pourcentage). Lecture/écriture android.graphics.PointF.

**Renvoie :**
android.graphics.PointF

### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```

Spécifie l'emplacement cible d'un effet de mouvement d'animation (en pourcentage).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public abstract PointF getBy()
```

Décrit la valeur de décalage relative de l'animation (en pourcentage). Lecture/écriture android.graphics.PointF.

**Renvoie :**
android.graphics.PointF

### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```

Décrit la valeur de décalage relative de l'animation (en pourcentage).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract PointF getRotationCenter()
```

Décrit le centre de rotation utilisé pour faire pivoter un chemin de mouvement d'un angle X. Lecture/écriture android.graphics.PointF.

**Renvoie :**
android.graphics.PointF

### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public abstract void setRotationCenter(PointF value)
```

Décrit le centre de rotation utilisé pour faire pivoter un chemin de mouvement d'un angle X.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Spécifie à quoi l'origine du chemin de mouvement est relative, comme la disposition de la diapositive ou le parent. Lecture/écriture [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Renvoie :**
int

### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

Spécifie à quoi l'origine du chemin de mouvement est relative, comme la disposition de la diapositive ou le parent. Lecture/écriture [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

Spécifie la primitive de chemin suivie des coordonnées pour le mouvement d'animation. Lecture/écriture [IMotionPath](../../com.aspose.slides/imotionpath).

**Renvoie :**
[IMotionPath](../../com.aspose.slides/imotionpath)

### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

Spécifie la primitive de chemin suivie des coordonnées pour le mouvement d'animation. Lecture/écriture [IMotionPath](../../com.aspose.slides/imotionpath).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

Spécifie comment le chemin de mouvement se déplace lorsque la forme est déplacée. Lecture/écriture [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Renvoie :**
int

### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

Spécifie comment le chemin de mouvement se déplace lorsque la forme est déplacée. Lecture/écriture [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

Décrit l'angle relatif du chemin de mouvement. Lecture/écriture float.

**Renvoie :**
float

### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

Décrit l'angle relatif du chemin de mouvement.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |