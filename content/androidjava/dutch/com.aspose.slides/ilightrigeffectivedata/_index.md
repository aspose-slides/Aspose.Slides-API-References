---
title: ILightRigEffectiveData
second_title: Aspose.Slides voor Android via Java API-referentie
description: Onveranderlijk object dat effectieve verlichtingsrig-eigenschappen bevat.
type: docs
url: /nl/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Onveranderlijk object dat effectieve verlichtingsrig-eigenschappen bevat.

--------------------

Deze interface wordt gebruikt als onderdeel van [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getDirection()](#getDirection--) | Lichtrichting. |
| [getLightType()](#getLightType--) | Stelt een vooraf ingestelde lichtrichtingsinstelling voor die op een vorm kan worden toegepast. |
| [getRotation()](#getRotation--) | Een rotatie wordt gedefinieerd door het gebruik van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een omwenteling rond de as zoals de breedte- en lengtegraadcoördinaten. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Lichtrichting. Alleen-lezen [LightingDirection](../../com.aspose.slides/lightingdirection).

**Retour:**  
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Stelt een vooraf ingestelde lichtrichtingsinstelling voor die op een vorm kan worden toegepast. Het lichtrig vertegenwoordigt een groep lichten die op een specifieke manier ten opzichte van een 3D-scène zijn georiënteerd. Alleen-lezen [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Retour:**  
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Een rotatie wordt gedefinieerd door het gebruik van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een omwenteling rond de as zoals de breedte- en lengtegraadcoördinaten. Eerste element in teruggegeven array - latitude, tweede - longitude, derde - revolutie.

**Retour:**  
float[] - Rotatiecoördinaten als float[]