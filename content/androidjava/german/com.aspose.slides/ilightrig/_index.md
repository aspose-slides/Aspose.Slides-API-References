---
title: ILightRig
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt LightRig dar.
type: docs
url: /de/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```


Stellt LightRig dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDirection()](#getDirection--) | Lichtrichtung. |
| [setDirection(int value)](#setDirection-int-) | Lichtrichtung. |
| [getLightType()](#getLightType--) | Stellt ein voreingestelltes Licht rechts dar, das auf eine Form angewendet werden kann. |
| [setLightType(int value)](#setLightType-int-) | Stellt ein voreingestelltes Licht rechts dar, das auf eine Form angewendet werden kann. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Eine Drehung wird durch die Verwendung einer Breitengrad-Koordinate, einer Längengrad-Koordinate und einer Umdrehung um die Achse definiert, wobei Breitengrad- und Längengrad-Koordinaten verwendet werden. |
| [getRotation()](#getRotation--) | Eine Drehung wird durch die Verwendung einer Breitengrad-Koordinate, einer Längengrad-Koordinate und einer Umdrehung um die Achse definiert, wobei Breitengrad- und Längengrad-Koordinaten verwendet werden. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


Lichtrichtung. Lesen/Schreiben [LightingDirection](../../com.aspose.slides/lightingdirection).

**Rückgabe:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```


Lichtrichtung. Lesen/Schreiben [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


Stellt ein voreingestelltes Licht rechts dar, das auf eine Form angewendet werden kann. Das LightRig stellt eine Gruppe von Lichtern dar, die in einer bestimmten Weise relativ zu einer 3D-Szene ausgerichtet sind. Lesen/Schreiben [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Rückgabe:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```


Stellt ein voreingestelltes Licht rechts dar, das auf eine Form angewendet werden kann. Das LightRig stellt eine Gruppe von Lichtern dar, die in einer bestimmten Weise relativ zu einer 3D-Szene ausgerichtet sind. Lesen/Schreiben [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```


Eine Drehung wird durch die Verwendung einer Breitengrad-Koordinate, einer Längengrad-Koordinate und einer Umdrehung um die Achse definiert, wobei Breitengrad- und Längengrad-Koordinaten verwendet werden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| latitude | float | Breitengrad-Koordinate float |
| longitude | float | Längengrad-Koordinate float |
| revolution | float | Revolution-Koordinate float |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Eine Drehung wird durch die Verwendung einer Breitengrad-Koordinate, einer Längengrad-Koordinate und einer Umdrehung um die Achse definiert, wobei Breitengrad- und Längengrad-Koordinaten verwendet werden. Erstes Element im Rückgabe-Array – latitude, zweites – longitude, drittes – revolution.

**Rückgabe:**
float[] – Rotationskoordinaten als float[]