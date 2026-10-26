---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective light rig properties.
type: docs
url: /fr/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Objet immuable qui contient les propriétés effectives du rig d’éclairage.

--------------------

Cette interface est utilisée dans le cadre de [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Méthodes

| Method | Description |
| --- | --- |
| [getDirection()](#getDirection--) | Direction de la lumière. |
| [getLightType()](#getLightType--) | Représente un éclairage prédéfini à droite qui peut être appliqué à une forme. |
| [getRotation()](#getRotation--) | Une rotation est définie par l’utilisation d’une coordonnée de latitude, d’une coordonnée de longitude et d’une révolution autour de l’axe comme coordonnées de latitude et de longitude. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Direction de la lumière. Lecture seule [LightingDirection](../../com.aspose.slides/lightingdirection).

**Renvoie:**  
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Représente un éclairage prédéfini à droite qui peut être appliqué à une forme. Le rig d’éclairage représente un groupe de lumières orientées d’une manière spécifique par rapport à une scène 3D. Lecture seule [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Renvoie:**  
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Une rotation est définillée par l’utilisation d’une coordonnée de latitude, d’une coordonnée de longitude et d’une révolution autour de l’axe comme coordonnées de latitude et de longitude. Premier élément du tableau retourné – latitude, deuxième – longitude, troisième – révolution.

**Renvoie:**  
float[] - Coordonnées de rotation en tant que float[]