---
title: LightRig
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente LightRig.
type: docs
url: /fr/com.aspose.slides/lightrig/
---
**Héritage:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Toutes les interfaces implémentées:**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

Représente LightRig.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | Light direction. |
| [setDirection(int value)](#setDirection-int-) | Light direction. |
| [getLightType()](#getLightType--) | Represents a preset light right that can be applied to a shape. |
| [setLightType(int value)](#setLightType-int-) | Represents a preset light right that can be applied to a shape. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |
| [getRotation()](#getRotation--) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Lecture seule long.

**Retourne:**
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```


Direction de la lumière. Lecture/écriture [LightingDirection](../../com.aspose.slides/lightingdirection).

**Retourne:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


Direction de la lumière. Lecture/écriture [LightingDirection](../../com.aspose.slides/lightingdirection).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public final int getLightType()
```


Représente un éclairage prédéfini pouvant être appliqué à une forme. Le light rig représente un groupe de lumières orientées d'une manière spécifique par rapport à une scène 3D. Lecture/écriture [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Retourne:**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```


Représente un éclairage prédéfini pouvant être appliqué à une forme. Le light rig représente un groupe de lumières orientées d'une manière spécifique par rapport à une scène 3D. Lecture/écriture [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```


Une rotation est définie par l'utilisation d'une coordonnée de latitude, d'une coordonnée de longitude et d'une révolution autour de l'axe comme coordonnées de latitude et de longitude. Si une des valeurs de coordonnées est Float.NaN, toute rotation est indéfinie.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```


Une rotation est définie par l'utilisation d'une coordonnée de latitude, d'une coordonnée de longitude et d'une révolution autour de l'axe comme coordonnées de latitude et de longitude. premier élément du tableau retourné - latitude, deuxième - longitude, troisième - révolution. Retourne null si aucune rotation définie.

**Retourne:**
float[]