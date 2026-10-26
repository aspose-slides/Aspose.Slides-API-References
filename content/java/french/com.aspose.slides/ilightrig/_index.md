---
title: ILightRig
second_title: Aspose.Slides for Java API Reference
description: Represents LightRig.
type: docs
url: /fr/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

Représente LightRig.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDirection()](#getDirection--) | Light direction. |
| [setDirection(int value)](#setDirection-int-) | Light direction. |
| [getLightType()](#getLightType--) | Represents a preset light right that can be applied to a shape. |
| [setLightType(int value)](#setLightType-int-) | Represents a preset light right that can be applied to a shape. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |
| [getRotation()](#getRotation--) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Direction de la lumière. Lecture/écriture [LightingDirection](../../com.aspose.slides/lightingdirection).

**Retourne :**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Direction de la lumière. Lecture/écriture [LightingDirection](../../com.aspose.slides/lightingdirection).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Représente une lumière prédéfinie à droite qui peut être appliquée à une forme. Le light rig représente un groupe de lumières orientées d'une manière spécifique par rapport à une scène 3D. Lecture/écriture [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Retourne :**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

Représente une lumière prédéfinie à droite qui peut être appliquée à une forme. Le light rig représente un groupe de lumières orientées d'une manière spécifique par rapport à une scène 3D. Lecture/écriture [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Une rotation est définie par l'utilisation d'une coordonnée de latitude, d'une coordonnée de longitude et d'une révolution autour de l'axe selon les coordonnées de latitude et de longitude.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| latitude | float | Coordonnée de latitude float |
| longitude | float | Coordonnée de longitude float |
| revolution | float | Coordonnée de révolution float |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Une rotation est définie par l'utilisation d'une coordonnée de latitude, d'une coordonnée de longitude et d'une révolution autour de l'axe selon les coordonnées de latitude et de longitude. premier élément du tableau retourné - latitude, deuxième - longitude, troisième - révolution.

**Retourne :**
float[] - Coordonnées de rotation sous forme de float[]