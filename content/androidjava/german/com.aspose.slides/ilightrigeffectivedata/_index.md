---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Unveränderliches Objekt, das wirksame LightRig-Eigenschaften enthält.
type: docs
url: /de/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Unveränderliches Objekt, das wirksame LightRig-Eigenschaften enthält.

--------------------

Dieses Interface wird als Teil von [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) verwendet.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDirection()](#getDirection--) | Lichtrichtung. |
| [getLightType()](#getLightType--) | Stellt ein voreingestelltes Licht rechts dar, das auf eine Form angewendet werden kann. |
| [getRotation()](#getRotation--) | Eine Rotation wird durch die Verwendung einer Breitengradkoordinate, einer Längengradkoordinate und einer Umdrehung um die Achse definiert, wobei die Breitengrad- und Längengradkoordinaten verwendet werden. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Lichtrichtung. Nur-Lesen [LightingDirection](../../com.aspose.slides/lightingdirection).

**Rückgabe:**
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Stellt ein voreingestelltes Licht rechts dar, das auf eine Form angewendet werden kann. Das LightRig stellt eine Gruppe von Lichtern dar, die in einer bestimmten Weise relativ zu einer 3D-Szene ausgerichtet sind. Nur-Lesen [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Rückgabe:**
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Eine Rotation wird durch die Verwendung einer Breitengradkoordinate, einer Längengradkoordinate und einer Umdrehung um die Achse definiert, wobei die Breitengrad- und Längengradkoordinaten verwendet werden. Erstes Element im Rückgabe-Array – Breitengrad, zweites – Längengrad, drittes – Umdrehung.

**Rückgabe:**
float[] - Rotationskoordinaten als float[]