---
title: LightRig
second_title: Aspose.Slides för Android via Java API-referens
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
| [getDirection()](#getDirection--) | Light direction. |
| [setDirection(int value)](#setDirection-int-) | Light direction. |
| [getLightType()](#getLightType--) | Represents a preset light right that can be applied to a shape. |
| [setLightType(int value)](#setLightType-int-) | Represents a preset light right that can be applied to a shape. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |
| [getRotation()](#getRotation--) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Endast läsning long.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public final int getLightType()
```


Representerar ett förinställt ljus åt höger som kan tillämpas på en form. Light rig representerar en grupp ljus orienterade på ett specifikt sätt i förhållande till en 3D-scen. Läs/skriv [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Returnerar:**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```


Representerar ett förinställt ljus åt höger som kan tillämpas på en form. Light rig representerar en grupp ljus orienterade på ett specifikt sätt i förhållande till en 3D-scen. Läs/skriv [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```


En rotation definieras genom användning av en latitudkoordinat, en longitudkoordinat och en revolution runt axeln enligt latitud- och longitudkoordinaterna. Om någon koordinatvärde är Float.NaN är hela rotationen odefinierad.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```


En rotation definieras genom användning av en latitudkoordinat, en longitudkoordinat och en revolution runt axeln enligt latitud- och longitudkoordinaterna. första elementet i returarrayen – latitud, andra – longitud, tredje – revolution. Returnerar null om ingen rotation definierad.

**Returnerar:**
float[]