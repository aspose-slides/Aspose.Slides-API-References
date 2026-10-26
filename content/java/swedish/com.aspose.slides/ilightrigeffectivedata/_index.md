---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Oföränderligt objekt som innehåller effektiva egenskaper för ljusrigg.
type: docs
url: /sv/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Oföränderligt objekt som innehåller effektiva ljusriggegenskaper.

--------------------

Detta gränssnitt används som en del av [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDirection()](#getDirection--) | Ljusriktning. |
| [getLightType()](#getLightType--) | Representerar en förinställd ljusrättning som kan tillämpas på en form. |
| [getRotation()](#getRotation--) | En rotation definieras genom användning av en latitudkoordinat, en longitudkoordinat och en revolution kring axiellen enligt latitud- och longitudkoordinaterna. |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Ljusriktning. Skrivskyddad [LightingDirection](../../com.aspose.slides/lightingdirection).

**Returnerar:**
int

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Representerar en förinställd ljusrättning som kan tillämpas på en form. Ljusriggen representerar en grupp ljus orienterade på ett specifikt sätt i förhållande till en 3D-scen. Skrivskyddad [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Returnerar:**
int

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

En rotation definieras genom användning av en latitudkoordinat, en longitudkoordinat och en revolution kring axiellen enligt latitud- och longitudkoordinaterna. Första elementet i returarrayen – latitud, andra – longitud, tredje – revolution.

**Returnerar:**
float[] - Rotationskoordinater som float[]