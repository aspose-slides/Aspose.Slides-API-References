---
title: LightRig
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt LightRig.
type: docs
url: /nl/com.aspose.slides/lightrig/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

Vertegenwoordigt LightRig.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | Lichtrichting. |
| [setDirection(int value)](#setDirection-int-) | Lichtrichting. |
| [getLightType()](#getLightType--) | Stelt een vooraf ingestelde lichtinstelling voor die op een vorm kan worden toegepast. |
| [setLightType(int value)](#setLightType-int-) | Stelt een vooraf ingestelde lichtinstelling voor die op een vorm kan worden toegepast. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Een rotatie wordt gedefinieerd door gebruik van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een revolutie rond de as als breedte- en lengtegraadcoördinaten. |
| [getRotation()](#getRotation--) | Een rotatie wordt gedefinieerd door gebruik van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een revolutie rond de as als breedte- en lengtegraadcoördinaten. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versie. Alleen-lezen long.

**Retour:**
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```

Lichtrichting. Lezen/Schrijven [LightingDirection](../../com.aspose.slides/lightingdirection).

**Retour:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```

Lichtrichting. Lezen/Schrijven [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public final int getLightType()
```

Stelt een vooraf ingestelde lichtinstelling voor die op een vorm kan worden toegepast. De light rig vertegenwoordigt een groep lichten die op een specifieke manier ten opzichte van een 3D-scene zijn georiënteerd. Lezen/Schrijven [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Retour:**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

Stelt een vooraf ingestelde lichtinstelling voor die op een vorm kan worden toegepast. De light rig vertegenwoordigt een groep lichten die op een specifieke manier ten opzichte van een 3D-scene zijn georiënteerd. Lezen/Schrijven [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Een rotatie wordt gedefinieerd door gebruik van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een revolutie rond de as als breedte- en lengtegraadcoördinaten. Als een van de coördinaatwaarden Float.NaN is, is de rotatie ongedefinieerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

Een rotatie wordt gedefinieerd door gebruik van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een revolutie rond de as als breedte- en lengtegraadcoördinaten. eerste element in de retourarray - latitude, tweede - longitude, derde - revolution. Retourneert null als er geen rotatie is gedefinieerd.

**Retour:**
float[]