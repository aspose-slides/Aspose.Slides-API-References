---
title: ILightRig
second_title: Aspose.Slides for Java API Reference
description: Represents LightRig.
type: docs
url: /de/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

Stellt LightRig dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDirection()](#getDirection--) | Licht-Richtung. |
| [setDirection(int value)](#setDirection-int-) | Licht-Richtung. |
| [getLightType()](#getLightType--) | Stellt ein voreingestelltes Licht rechts dar, das auf eine Form angewendet werden kann. |
| [setLightType(int value)](#setLightType-int-) | Stellt ein voreingestelltes Licht rechts dar, das auf eine Form angewendet werden kann. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Eine Rotation wird definiert durch die Verwendung einer Breitengradkoordinate, einer Längengradkoordinate und einer Umdrehung um die Achse als Breitengrad- und Längengradkoordinate. |
| [getRotation()](#getRotation--) | Eine Rotation wird definiert durch die Verwendung einer Breitengradkoordinate, einer Längengradkoordinate und einer Umdrehung um die Achse als Breitengrad- und Längengradkoordinate. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Licht-Richtung. Lesen/Schreiben [LightingDirection](../../com.aspose.slides/lightingdirection).

**Rückgabewert:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Licht-Richtung. Lesen/Schreiben [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Stellt ein voreingestelltes Licht rechts dar, das auf eine Form angewendet werden kann. Der LightRig stellt eine Gruppe von Lichtern dar, die in einer bestimmten Weise relativ zu einer 3D-Szene ausgerichtet sind. Lesen/Schreiben [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Rückgabewert:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

Stellt ein voreingestelltes Licht rechts dar, das auf eine Form angewendet werden kann. Der LightRig stellt eine Gruppe von Lichtern dar, die in einer bestimmten Weise relativ zu einer 3D-Szene ausgerichtet sind. Lesen/Schreiben [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Eine Rotation wird definiert durch die Verwendung einer Breitengradkoordinate, einer Längengradkoordinate und einer Umdrehung um die Achse als Breitengrad- und Längengradkoordinate.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| latitude | float | Breitengradkoordinate float |
| longitude | float | Längengradkoordinate float |
| revolution | float | Umdrehungskoordinate float |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Eine Rotation wird definiert durch die Verwendung einer Breitengradkoordinate, einer Längengradkoordinate und einer Umdrehung um die Achse als Breitengrad- und Längengradkoordinate. Erstes Element im Rückgabe-Array – Breitengrad, zweites – Längengrad, drittes – Umdrehung.

**Rückgabewert:**
float[] - Rotationskoordinaten als float[]