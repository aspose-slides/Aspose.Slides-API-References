---
title: IPresetShadow
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente un effet d'ombre prédéfini.
type: docs
url: /fr/com.aspose.slides/ippresetshadow/
---
**Toutes les interfaces implémentées:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

Représente un effet d'ombre prédéfini.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDirection()](#getDirection--) | Direction de l'ombre. |
| [setDirection(float value)](#setDirection-float-) | Direction de l'ombre. |
| [getDistance()](#getDistance--) | Distance de l'ombre. |
| [setDistance(double value)](#setDistance-double-) | Distance de l'ombre. |
| [getShadowColor()](#getShadowColor--) | Couleur de l'ombre. |
| [getPreset()](#getPreset--) | Préréglage. |
| [setPreset(int value)](#setPreset-int-) | Préréglage. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Direction de l'ombre. Lecture/écriture float.

**Renvoie:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Direction de l'ombre. Lecture/écriture float.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Distance de l'ombre. Lecture/écriture double.

**Renvoie:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Distance de l'ombre. Lecture/écriture double.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Couleur de l'ombre. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

Préréglage. Lecture/écriture [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Renvoie:**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```

Préréglage. Lecture/écriture [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |