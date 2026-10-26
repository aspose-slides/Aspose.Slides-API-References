---
title: LightRig
second_title: Aspose.Slides för Java API-referens
description: Representerar LightRig.
type: docs
url: /sv/com.aspose.slides/lightrig/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

Representerar LightRig.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | Ljusriktning. |
| [setDirection(int value)](#setDirection-int-) | Ljusriktning. |
| [getLightType()](#getLightType--) | Representerar en förinställd ljusrätt som kan tillämpas på en form. |
| [setLightType(int value)](#setLightType-int-) | Representerar en förinställd ljusrätt som kan tillämpas på en form. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | En rotation definieras genom användning av en latitudkoordinat, en longitudkoordinat och en rotation kring axeln som latitud- och longitudkoordinaterna. |
| [getRotation()](#getRotation--) | En rotation definieras genom användning av en latitudkoordinat, en longitudkoordinat och en rotation kring axeln som latitud- och longitudkoordinaterna. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Skrivskyddad long.

**Returnerar:**
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```


Ljusriktning. Läs/skriv [LightingDirection](../../com.aspose.slides/lightingdirection).

**Returnerar:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


Ljusriktning. Läs/skriv [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public final int getLightType()
```


Representerar en förinställd ljusrätt som kan tillämpas på en form. Light rig representerar en grupp av ljus orienterade på ett specifikt sätt i förhållande till en 3D-scen. Läs/skriv [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Returnerar:**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```


Representerar en förinställd ljusrätt som kan tillämpas på en form. Light rig representerar en grupp av ljus orienterade på ett specifikt sätt i förhållande till en 3D-scen. Läs/skriv [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```


En rotation definieras genom användning av en latitudkoordinat, en longitudkoordinat och en rotation kring axeln som latitud- och longitudkoordinaterna. Om något koordinatvärde är Float.NaN är hela rotationen odefinierad.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public final float[] getRotation()
```


En rotation definieras genom användning av en latitudkoordinat, en longitudkoordinat och en rotation kring axeln som latitud- och longitudkoordinaterna. Första elementet i returarrayen - latitud, andra - longitud, tredje - rotation. Returnerar null om ingen rotation definierats.

**Returnerar:**
float[]