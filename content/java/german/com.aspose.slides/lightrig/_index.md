---
title: LightRig
second_title: Aspose.Slides für Java API Referenz
description: Stellt LightRig dar.
type: docs
url: /de/com.aspose.slides/lightrig/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

Stellt LightRig dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | Lichtausrichtung. |
| [setDirection(int value)](#setDirection-int-) | Lichtausrichtung. |
| [getLightType()](#getLightType--) | Stellt ein vordefiniertes Licht rechts dar, das auf eine Form angewendet werden kann. |
| [setLightType(int value)](#setLightType-int-) | Stellt ein vordefiniertes Licht rechts dar, das auf eine Form angewendet werden kann. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Eine Rotation wird durch die Verwendung eines Breitengradkoordinaten, eines Längengradkoordinaten und einer Umdrehung um die Achse als Breitengrad- und Längengradkoordinaten definiert. |
| [getRotation()](#getRotation--) | Eine Rotation wird durch die Verwendung eines Breitengradkoordinaten, eines Längengradkoordinaten und einer Umdrehung um die Achse als Breitengrad- und Längengradkoordinaten definiert. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Nur-Lesen long.

**Rückgabewert:**
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```


Lichtausrichtung. Lesen/Schreiben [LightingDirection](../../com.aspose.slides/lightingdirection).

**Rückgabewert:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


Lichtausrichtung. Lesen/Schreiben [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public final int getLightType()
```


Stellt ein vordefiniertes Licht rechts dar, das auf eine Form angewendet werden kann. Das LightRig stellt eine Gruppe von Lichtern dar, die in einer bestimmten Weise relativ zu einer 3D-Szene ausgerichtet sind. Lesen/Schreiben [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Rückgabewert:**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```


Stellt ein vordefiniertes Licht rechts dar, das auf eine Form angewendet werden kann. Das LightRig stellt eine Gruppe von Lichtern dar, die in einer bestimmten Weise relativ zu einer 3D-Szene ausgerichtet sind. Lesen/Schreiben [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```


Eine Rotation wird durch die Verwendung eines Breitengradkoordinaten, eines Längengradkoordinaten und einer Umdrehung um die Achse als Breitengrad- und Längengradkoordinaten definiert. Wenn ein Koordinatenwert Float.NaN ist, ist die gesamte Rotation undefiniert.

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


Eine Rotation wird durch die Verwendung eines Breitengradkoordinaten, eines Längengradkoordinaten und einer Umdrehung um die Achse als Breitengrad- und Längengradkoordinaten definiert. Erstes Element im Rückgabe-Array – Breitengrad, zweites – Längengrad, drittes – Umdrehung. Gibt null zurück, wenn keine Rotation definiert ist.

**Rückgabewert:**
float[]