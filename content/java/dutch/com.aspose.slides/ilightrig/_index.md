---
title: ILightRig
second_title: Aspose.Slides for Java API Reference
description: Stelt LightRig voor.
type: docs
url: /nl/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

Stelt LightRig voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getDirection()](#getDirection--) | Lichtrichting. |
| [setDirection(int value)](#setDirection-int-) | Lichtrichting. |
| [getLightType()](#getLightType--) | Stelt een vooraf ingestelde rechtsverlichting voor die op een vorm kan worden toegepast. |
| [setLightType(int value)](#setLightType-int-) | Stelt een vooraf ingestelde rechtsverlichting voor die op een vorm kan worden toegepast. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Een rotatie wordt gedefinieerd door gebruik te maken van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een revolutie rond de as als de breedtegraad- en lengtegraadcoördinaten. |
| [getRotation()](#getRotation--) | Een rotatie wordt gedefinieerd door gebruik te maken van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een revolutie rond de as als de breedtegraad- en lengtegraadcoördinaten. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


Lichtrichting. Lezen/schrijven [LightingDirection](../../com.aspose.slides/lightingdirection).

**Retour:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```


Lichtrichting. Lezen/schrijven [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


Stelt een vooraf ingestelde rechtsverlichting voor die op een vorm kan worden toegepast. De light rig vertegenwoordigt een groep verlichting die op een specifieke manier is georiënteerd ten opzichte van een 3D-scene. Lezen/schrijven [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Retour:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```


Stelt een vooraf ingestelde rechtsverlichting voor die op een vorm kan worden toegepast. De light rig vertegenwoordigt een groep verlichting die op een specifieke manier is georiënteerd ten opzichte van een 3D-scene. Lezen/schrijven [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```


Een rotatie wordt gedefinieerd door gebruik te maken van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een revolutie rond de as als de breedtegraad- en lengtegraadcoördinaten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| latitude | float | Breedtegraadcoördinaat float |
| longitude | float | Lengtegraadcoördinaat float |
| revolution | float | Revolutiecoördinaat float |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Een rotatie wordt gedefinieerd door gebruik te maken van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een revolutie rond de as als de breedtegraad- en lengtegraadcoördinaten. eerste element in geretourneerde array - breedtegraad, tweede - lengtegraad, derde - revolutie.

**Retour:**
float[] - Rotatiecoördinaten als float[]