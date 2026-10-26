---
title: LightRig
second_title: Aspose.Slides voor Java API-referentie
description: Stelt LightRig voor.
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

Stelt LightRig voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | Lichtrichting. |
| [setDirection(int value)](#setDirection-int-) | Lichtrichting. |
| [getLightType()](#getLightType--) | Stelt een voorgedefinieerd licht rechts voor dat kan worden toegepast op een vorm. |
| [setLightType(int value)](#setLightType-int-) | Stelt een voorgedefinieerd licht rechts voor dat kan worden toegepast op een vorm. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Een rotatie wordt gedefinieerd door het gebruik van een latitude-coördinaat, een longitude-coördinaat en een revolutie rond de as als de latitude- en longitude-coördinaten. |
| [getRotation()](#getRotation--) | Een rotatie wordt gedefinieerd door het gebruik van een latitude-coördinaat, een longitude-coördinaat en een revolutie rond de as als de latitude- en longitude-coördinaten. |
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

Stelt een voorgedefinieerd licht rechts voor dat kan worden toegepast op een vorm. De light rig stelt een groep lichten voor die op een specifieke manier is georiënteerd ten opzichte van een 3D-scene. Lezen/Schrijven [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Retour:**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

Stelt een voorgedefinieerd licht rechts voor dat kan worden toegepast op een vorm. De light rig stelt een groep lichten voor die op een specifieke manier is georiënteerd ten opzichte van een 3D-scene. Lezen/Schrijven [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Een rotatie wordt gedefinieerd door het gebruik van een latitude-coördinaat, een longitude-coördinaat en een revolutie rond de as als de latitude- en longitude-coördinaten. Als een van de coördinatiewaarden Float.NaN is, is de gehele rotatie ongedefinieerd.

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

Een rotatie wordt gedefinieerd door het gebruik van een latitude-coördinaat, een longitude-coördinaat en een revolutie rond de as als de latitude- en longitude-coördinaten. Eerste element in het geretourneerde array - latitude, tweede - longitude, derde - revolution. Retourneert null als er geen rotatie is gedefinieerd.

**Retour:**
float[]