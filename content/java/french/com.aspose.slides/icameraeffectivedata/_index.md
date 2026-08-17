---
title: ICameraEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Objet immutable qui contient les propriétés effectives de la caméra.
type: docs
url: /fr/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

Objet immutable qui contient les propriétés effectives de la caméra.

--------------------

Cette interface est utilisée comme partie de [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCameraType()](#getCameraType--) | Type de caméra. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | FOV de la caméra (0-180 deg, champ de vision). |
| [getZoom()](#getZoom--) | Zoom de la caméra (valeur positive en pourcentage). |
| [getRotation()](#getRotation--) | Une rotation est définie par l'utilisation d'une coordonnée de latitude, d'une coordonnée de longitude et d'une révolution autour de l'axe comme coordonnées de latitude et de longitude. |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Type de caméra. Lecture seule [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Renvoie:**
int

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

FOV de la caméra (0-180 deg, champ de vision). Lecture seule float.

**Renvoie:**
float

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Zoom de la caméra (valeur positive en pourcentage). Lecture seule float.

**Renvoie:**
float

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Une rotation est définie par l'utilisation d'une coordonnée de latitude, d'une coordonnée de longitude et d'une révolution autour de l'axe comme coordonnées de latitude et de longitude. premier élément du tableau retourné - latitude, deuxième - longitude, troisième - révolution. Renvoie null si aucune rotation n'est définie.

**Renvoie:**
float[] - Tableau des valeurs de rotation en tant que float[].