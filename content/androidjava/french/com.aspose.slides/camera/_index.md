---
title: Camera
second_title: Référence API Java Aspose.Slides pour Android
description: Représente la caméra.
type: docs
url: /fr/com.aspose.slides/camera/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Toutes les interfaces implémentées :**
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)
```
public final class Camera extends PVIObject implements ICamera
```

Représente la caméra.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | Type de caméra. |
| [setCameraType(int value)](#setCameraType-int-) | Type de caméra. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Champ de vision de la caméra (0-180 degrés, champ de vision). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Champ de vision de la caméra (0-180 degrés, champ de vision). |
| [getZoom()](#getZoom--) | Zoom de la caméra (valeur positive en pourcentage). |
| [setZoom(float value)](#setZoom-float-) | Zoom de la caméra (valeur positive en pourcentage). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Une rotation est définie à l'aide d'une coordonnée de latitude, d'une coordonnée de longitude et d'une révolution autour de l'axe correspondant aux coordonnées de latitude et de longitude. |
| [getRotation()](#getRotation--) | Une rotation est définie à l'aide d'une coordonnée de latitude, d'une coordonnée de longitude et d'une révolution autour de l'axe correspondant aux coordonnées de latitude et de longitude. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Long en lecture seule.

**Renvoie :**
long

### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```

Type de caméra. Lecture/écriture [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Renvoie :**
int

### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```

Type de caméra. Lecture/écriture [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```

Champ de vision de la caméra (0-180 degrés, champ de vision). Lecture/écriture float.

**Renvoie :**
float

### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

Champ de vision de la caméra (0-180 degrés, champ de vision). Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public final float getZoom()
```

Zoom de la caméra (valeur positive en pourcentage). Lecture/écriture float.

**Renvoie :**
float

### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```

Zoom de la caméra (valeur positive en pourcentage). Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Une rotation est définie à l'aide d'une coordonnée de latitude, d'une coordonnée de longitude et d'une révolution autour de l'axe correspondant aux coordonnées de latitude et de longitude. Si l'une des valeurs de coordonnées est Float.NaN, toute rotation est indéfinie.

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

Une rotation est définie à l'aide d'une coordonnée de latitude, d'une coordonnée de longitude et d'une révolution autour de l'axe correspondant aux coordonnées de latitude et de longitude. premier élément du tableau retourné – latitude, deuxième – longitude, troisième – révolution. Renvoie null si aucune rotation n'est définie.

**Renvoie :**
float[]