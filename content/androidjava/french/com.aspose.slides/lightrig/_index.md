---
title: LightRig
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente LightRig.
type: docs
url: /fr/com.aspose.slides/lightrig/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Toutes les interfaces implémentées :**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

Représente LightRig.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | Direction de la lumière. |
| [setDirection(int value)](#setDirection-int-) | Direction de la lumière. |
| [getLightType()](#getLightType--) | Représente une lumière prédéfinie à droite qui peut être appliquée à une forme. |
| [setLightType(int value)](#setLightType-int-) | Représente une lumière prédéfinie à droite qui peut être appliquée à une forme. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Une rotation est définie par l’utilisation d’une coordonnée de latitude, d’une coordonnée de longitude, et d’une révolution autour de l’axe comme coordonnées de latitude et de longitude. |
| [getRotation()](#getRotation--) | Une rotation est définie par l’utilisation d’une coordonnée de latitude, d’une coordonnée de longitude, et d’une révolution autour de l’axe comme coordonnées de latitude et de longitude. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Lecture seule long.

**Renvoie :**
long

### getDirection() {#getDirection--}
```
public final int getDirection()
```

Direction de la lumière. Lecture/écriture [LightingDirection](../../com.aspose.slides/lightingdirection).

**Renvoie :**
int

### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```

Direction de la lumière. Lecture/écriture [LightingDirection](../../com.aspose.slides/lightingdirection).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public final int getLightType()
```

Représente une lumière prédéfinie à droite qui peut être appliquée à une forme. Le système d’éclairage représente un groupe de lumières orientées d’une manière spécifique par rapport à une scène 3D. Lecture/écriture [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Renvoie :**
int

### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

Représente une lumière prédéfinie à droite qui peut être appliquée à une forme. Le système d’éclairage représente un groupe de lumières orientées d’une manière spécifique par rapport à une scène 3D. Lecture/écriture [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Une rotation est définie par l’utilisation d’une coordonnée de latitude, d’une coordonnée de longitude, et d’une révolution autour de l’axe comme coordonnées de latitude et de longitude. Si l’une des valeurs de coordonnées est Float.NaN, toute la rotation est indéfinie.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

Une rotation est définie par l’utilisation d’une coordonnée de latitude, d’une coordonnée de longitude, et d’une révolution autour de l’axe comme coordonnées de latitude et de longitude. Le premier élément du tableau renvoyé – latitude, le second – longitude, le troisième – révolution. Renvoie null si aucune rotation n’est définie.

**Renvoie :**
float[]