---
title: LightRig
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt LightRig dar.
type: docs
url: /de/com.aspose.slides/lightrig/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

Stellt LightRig dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | Lichtrichtung. |
| [setDirection(int value)](#setDirection-int-) | Lichtrichtung. |
| [getLightType()](#getLightType--) | Stellt ein voreingestelltes Licht rechts dar, das auf eine Form angewendet werden kann. |
| [setLightType(int value)](#setLightType-int-) | Stellt ein voreingestelltes Licht rechts dar, das auf eine Form angewendet werden kann. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Eine Drehung wird durch die Verwendung einer latitude-Koordinate, einer longitude-Koordinate und einer revolution um die Achse definiert, wie die latitude- und longitude-Koordinaten. |
| [getRotation()](#getRotation--) | Eine Drehung wird durch die Verwendung einer latitude-Koordinate, einer longitude-Koordinate und einer revolution um die Achse definiert, wie die latitude- und longitude-Koordinaten. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur lesbar long.

**Rückgabe:**
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```

Lichtrichtung. Lese-/Schreib-[LightingDirection](../../com.aspose.slides/lightingdirection).

**Rückgabe:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```

Lichtrichtung. Lese-/Schreib-[LightingDirection](../../com.aspose.slides/lightingdirection).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public final int getLightType()
```

Stellt ein voreingestelltes Licht rechts dar, das auf eine Form angewendet werden kann. Das LightRig stellt eine Gruppe von Lichtern dar, die in einer bestimmten Weise relativ zu einer 3D-Szene ausgerichtet sind. Lese-/Schreib-[LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Rückgabe:**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

Stellt ein voreingestelltes Licht rechts dar, das auf eine Form angewendet werden kann. Das LightRig stellt eine Gruppe von Lichtern dar, die in einer bestimmten Weise relativ zu einer 3D-Szene ausgerichtet sind. Lese-/Schreib-[LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Eine Drehung wird durch die Verwendung einer latitude-Koordinate, einer longitude-Koordinate und einer revolution um die Achse definiert, wie die latitude- und longitude-Koordinaten. Wenn irgendein Koordinatenwert Float.NaN ist, ist die gesamte Drehung nicht definiert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

Eine Drehung wird durch die Verwendung einer latitude-Koordinate, einer longitude-Koordinate und einer revolution um die Achse definiert, wie die latitude- und longitude-Koordinaten. Erstes Element im Rückgabe-Array – latitude, zweites – longitude, drittes – revolution. Gibt null zurück, wenn keine Drehung definiert ist.

**Rückgabe:**
float[]