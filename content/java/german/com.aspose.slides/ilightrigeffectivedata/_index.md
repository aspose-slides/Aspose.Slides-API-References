---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective light rig properties.
type: docs
url: /de/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Unveränderliches Objekt, das die effektiven Lichtrig-Eigenschaften enthält.

--------------------

Dieses Interface wird als Teil von [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) verwendet.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDirection()](#getDirection--) | Lichtrichtung. |
| [getLightType()](#getLightType--) | Stellt ein vordefiniertes Licht dar, das auf eine Form angewendet werden kann. |
| [getRotation()](#getRotation--) | Eine Drehung wird definiert durch die Verwendung einer Breitengrad-Koordinate, einer Längengrad-Koordinate und einer Drehung um die Achse als Breitengrad- und Längengrad-Koordinaten. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


Lichtrichtung. Nur lesbar [LightingDirection](../../com.aspose.slides/lightingdirection).

**Rückgabe:**
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


Stellt ein vordefiniertes Licht dar, das auf eine Form angewendet werden kann. Das Lichtrig repräsentiert eine Gruppe von Lichtern, die in einer bestimmten Weise relativ zu einer 3D-Szene ausgerichtet sind. Nur lesbar [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Rückgabe:**
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Eine Drehung wird definiert durch die Verwendung einer Breitengrad-Koordinate, einer Längengrad-Koordinate und einer Drehung um die Achse als Breitengrad- und Längengrad-Koordinaten. Erstes Element im Rückgabe-Array – Breitengrad, zweites – Längengrad, drittes – Revolution.

**Rückgabe:**
float[] - Rotationskoordinaten als float[]