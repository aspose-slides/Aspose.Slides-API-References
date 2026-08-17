---
title: ICamera
second_title: Aspose.Slides for Java API Reference
description: Represents Camera.
type: docs
url: /fr/com.aspose.slides/icamera/
---```
public interface ICamera
```

Représente une caméra.
## Méthodes

| Method | Description |
| --- | --- |
| [getCameraType()](#getCameraType--) | Type de caméra Lecture/écriture [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | Type de caméra Lecture/écriture [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Champ de vision de la caméra (0-180 deg, champ de vision) Lecture/écriture float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Champ de vision de la caméra (0-180 deg, champ de vision) Lecture/écriture float. |
| [getZoom()](#getZoom--) | Zoom de la caméra (valeur positive en pourcentage) Lecture/écriture float. |
| [setZoom(float value)](#setZoom-float-) | Zoom de la caméra (valeur positive en pourcentage) Lecture/écriture float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Une rotation est définie par l’utilisation d’une coordonnée de latitude, d’une coordonnée de longitude et d’une révolution autour de l’axe correspondant aux coordonnées de latitude et de longitude. |
| [getRotation()](#getRotation--) | Une rotation est définie par l’utilisation d’une coordonnée de latitude, d’une coordonnée de longitude et d’une révolution autour de l’axe correspondant aux coordonnées de latitude et de longitude. |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Type de caméra Lecture/écriture [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Renvoie :**
int

### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

Type de caméra Lecture/écriture [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

Champ de vision de la caméra (0-180 deg, champ de vision) Lecture/écriture float.

**Renvoie :**
float

### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

Champ de vision de la caméra (0-180 deg, champ de vision) Lecture/écriture float.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Zoom de la caméra (valeur positive en pourcentage) Lecture/écriture float.

**Renvoie :**
float

### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

Zoom de la caméra (valeur positive en pourcentage) Lecture/écriture float.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Une rotation est définie par l’utilisation d’une coordonnée de latitude, d’une coordonnée de longitude et d’une révolution autour de l’axe correspondant aux coordonnées de latitude et de longitude. Si la valeur d’une des coordonnées est Float.NaN, toute la rotation est indéfinie.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| latitude | float | Valeur de latitude float |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Une rotation est définie par l’utilisation d’une coordonnée de latitude, d’une coordonnée de longitude et d’une révolution autour de l’axe correspondant aux coordonnées de latitude et de longitude. Premier élément du tableau retourné - latitude, deuxième - longitude, troisième - révolution. Renvoie null si aucune rotation n’est définie.

**Renvoie :**
float[] - Tableau des valeurs de rotation sous forme de float[].