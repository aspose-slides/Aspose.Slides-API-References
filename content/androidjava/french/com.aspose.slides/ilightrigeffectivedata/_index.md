---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective light rig properties.
type: docs
url: /fr/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Objet immuable qui contient les propriétés effectives du rig lumineux.

--------------------

Cette interface est utilisée comme partie de [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDirection()](#getDirection--) | Direction de la lumière. |
| [getLightType()](#getLightType--) | Représente un éclairage prédéfini qui peut être appliqué à une forme. |
| [getRotation()](#getRotation--) | Une rotation est définie à l’aide d’une coordonnée de latitude, d’une coordonnée de longitude et d’une révolution autour de l’axe correspondant aux coordonnées de latitude et de longitude. |

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

Représente un éclairage prédéfini qui peut être appliqué à une forme. Le rig lumineux représente un groupe de lumières orientées d’une façon spécifique par rapport à une scène 3D. Lecture seule [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Renvoie:**  
int  

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Une rotation est définie à l’aide d’une coordonnée de latitude, d’une coordonnée de longitude et d’une révolution autour de l’axe correspondant aux coordonnées de latitude et de longitude. Premier élément du tableau retourné : latitude, deuxième : longitude, troisième : révolution.

**Renvoie:**  
float[] – Coordonnées de rotation en tant que float[]