---
title: ILightRig
second_title: Aspose.Slides pour Android via Référence de l'API Java
description: Représente LightRig.
type: docs
url: /fr/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

Représente LightRig.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDirection()](#getDirection--) | Direction de la lumière. |
| [setDirection(int value)](#setDirection-int-) | Direction de la lumière. |
| [getLightType()](#getLightType--) | Représente une lumière prédéfinie à droite qui peut être appliquée à une forme. |
| [setLightType(int value)](#setLightType-int-) | Représente une lumière prédéfinie à droite qui peut être appliquée à une forme. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Une rotation est définie à l'aide d'une coordonnée de latitude, d'une coordonnée de longitude et d'une révolution autour de l'axe selon les coordonnées de latitude et de longitude. |
| [getRotation()](#getRotation--) | Une rotation est définie à l'aide d'une coordonnée de latitude, d'une coordonnée de longitude et d'une révolution autour de l'axe selon les coordonnées de latitude et de longitude. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Direction de la lumière. Lecture/écriture [LightingDirection](../../com.aspose.slides/lightingdirection).

**Retour:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Direction de la lumière. Lecture/écriture [LightingDirection](../../com.aspose.slides/lightingdirection).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Représente une lumière prédéfinie à droite qui peut être appliquée à une forme. Le rig lumineux représente un groupe de lumières orientées d'une façon spécifique par rapport à une scène 3D. Lecture/écriture [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Retour:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

Représente une lumière prédéfinie à droite qui peut être appliquée à une forme. Le rig lumineux représente un groupe de lumières orientées d'une façon spécifique par rapport à une scène 3D. Lecture/écriture [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Une rotation est définie à l'aide d'une coordonnée de latitude, d'une coordonnée de longitude et d'une révolution autour de l'axe selon les coordonnées de latitude et de longitude.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| latitude | float | Coordonnée de latitude float |
| longitude | float | Coordonnée de longitude float |
| revolution | float | Coordonnée de révolution float |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Une rotation est définie à l'aide d'une coordonnée de latitude, d'une coordonnée de longitude et d'une révolution autour de l'axe selon les coordonnées de latitude et de longitude. premier élément du tableau retourné - latitude, deuxième - longitude, troisième - révolution.

**Retour:**
float[] - Coordonnées de rotation sous forme de float[]