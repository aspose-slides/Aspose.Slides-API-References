---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective light rig properties.
type: docs
url: /nl/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Onveranderlijk object dat effectieve lichtrig-eigenschappen bevat.

--------------------

Deze interface wordt gebruikt als onderdeel van [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getDirection()](#getDirection--) | Lichtrichting. |
| [getLightType()](#getLightType--) | Vertegenwoordigt een vooraf ingestelde lichtinstelling die op een vorm kan worden toegepast. |
| [getRotation()](#getRotation--) | Een rotatie wordt gedefinieerd door het gebruik van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een omwenteling rond de as als de breedte- en lengtegraadcoördinaten. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


Lichtrichting. Alleen-lezen [LightingDirection](../../com.aspose.slides/lightingdirection).

**Retourneert:**
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


Vertegenwoordigt een vooraf ingestelde lichtinstelling die op een vorm kan worden toegepast. De lichtrig vertegenwoordigt een groep lichten die op een specifieke manier zijn georiënteerd ten opzichte van een 3D-scène. Alleen-lezen [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Retourneert:**
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Een rotatie wordt gedefinieerd door het gebruik van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een omwenteling rond de as als de breedte- en lengtegraadcoördinaten. Eerste element in het retourarray - breedtegraad, tweede - lengtegraad, derde - omwenteling.

**Retourneert:**
float[] - Rotatiecoördinaten als float[]