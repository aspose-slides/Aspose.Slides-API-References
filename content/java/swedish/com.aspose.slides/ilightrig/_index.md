---
title: ILightRig
second_title: Aspose.Slides for Java API Reference
description: Representerar LightRig.
type: docs
url: /sv/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

Representerar LightRig.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDirection()](#getDirection--) | Ljusriktning. |
| [setDirection(int value)](#setDirection-int-) | Ljusriktning. |
| [getLightType()](#getLightType--) | Representerar ett förinställt ljus som kan tillämpas på en form. |
| [setLightType(int value)](#setLightType-int-) | Representerar ett förinställt ljus som kan tillämpas på en form. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | En rotation definieras genom användning av en latitudkoordinat, en longitudkoordinat och en revolution kring axeln som latitud- och longitudkoordinaterna. |
| [getRotation()](#getRotation--) | En rotation definieras genom användning av en latitudkoordinat, en longitudkoordinat och en revolution kring axeln som latitud- och longitudkoordinaterna. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Ljusriktning. Läs/skriv [LightingDirection](../../com.aspose.slides/lightingdirection).

**Returnerar:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Ljusriktning. Läs/skriv [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Representerar ett förinställt ljus som kan tillämpas på en form. Ljusriget representerar en grupp ljus orienterade på ett specifikt sätt i förhållande till en 3D-scen. Läs/skriv [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Returnerar:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

Representerar ett förinställt ljus som kan tillämpas på en form. Ljusriget representerar en grupp ljus orienterade på ett specifikt sätt i förhållande till en 3D-scen. Läs/skriv [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

En rotation definieras genom användning av en latitudkoordinat, en longitudkoordinat och en revolution kring axeln som latitud- och longitudkoordinaterna.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| latitude | float | Latitudkoordinat float |
| longitude | float | Longitudkoordinat float |
| revolution | float | Revolutionskoordinat float |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

En rotation definieras genom användning av en latitudkoordinat, en longitudkoordinat och en revolution kring axeln som latitud- och longitudkoordinaterna. första elementet i returarrayen - latitud, andra - longitud, tredje - revolution.

**Returnerar:**
float[] - Rotationskoordinater som float[]