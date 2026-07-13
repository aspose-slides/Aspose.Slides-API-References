---
title: ILightRig
second_title: Aspose.Slides for Android via Java API Reference
description: Represents LightRig.
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
| [getLightType()](#getLightType--) | Stelt een vooraf ingestelde lichtinstelling rechts voor die kan worden toegepast op een vorm. |
| [setLightType(int value)](#setLightType-int-) | Stelt een vooraf ingestelde lichtinstelling rechts voor die kan worden toegepast op een vorm. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Een rotatie wordt gedefinieerd door het gebruik van een latitude-coördinaat, een longitude-coördinaat en een revolutie rond de as als de latitude- en longitude-coördinaten. |
| [getRotation()](#getRotation--) | Een rotatie wordt gedefinieerd door het gebruik van een latitude-coördinaat, een longitude-coördinaat en een revolutie rond de as als de latitude- en longitude-coördinaten. |
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


Stelt een vooraf ingestelde lichtinstelling rechts voor die kan worden toegepast op een vorm. De light rig vertegenwoordigt een groep lichten die op een specifieke manier ten opzichte van een 3D-scène zijn georiënteerd. Lezen/schrijven [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Retour:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```


Stelt een vooraf ingestelde lichtinstelling rechts voor die kan worden toegepast op een vorm. De light rig vertegenwoordigt een groep lichten die op een specifieke manier ten opzichte van een 3D-scène zijn georiënteerd. Lezen/schrijven [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```


Een rotatie wordt gedefinieerd door het gebruik van een latitude-coördinaat, een longitude-coördinaat en een revolutie rond de as als de latitude- en longitude-coördinaten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| latitude | float | Latitude-coördinaat float |
| longitude | float | Longitude-coördinaat float |
| revolution | float | Revolutie-coördinaat float |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Een rotatie wordt gedefinieerd door het gebruik van een latitude-coördinaat, een longitude-coördinaat en een revolutie rond de as als de latitude- en longitude-coördinaten. eerste element in het teruggegeven array - latitude, tweede - longitude, derde - revolution.

**Retour:**
float[] - Rotatiecoördinaten als float[]