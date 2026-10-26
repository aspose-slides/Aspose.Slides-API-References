---
title: ILightRigEffectiveData
second_title: Aspose.Slides för Android via Java API-referens
description: Oföränderligt objekt som innehåller de effektiva egenskaperna för ljusrigg.
type: docs
url: /sv/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Oföränderligt objekt som innehåller de effektiva egenskaperna för ljusrigg.

--------------------

Detta gränssnitt används som en del av [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDirection()](#getDirection--) | Ljusriktning. |
| [getLightType()](#getLightType--) | Representerar en förinställd ljusrättning som kan tillämpas på en form. |
| [getRotation()](#getRotation--) | En rotation definieras genom användning av en latitude-koordinat, en longitude-koordinat och en revolution kring axeln som latitude- och longitude-koordinaterna. |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Ljusriktning. Endast läsning [LightingDirection](../../com.aspose.slides/lightingdirection).

**Returnerar:**
int

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Representerar en förinställd ljusrättning som kan tillämpas på en form. Ljusriggen representerar en grupp ljus orienterade på ett specifikt sätt i förhållande till en 3D-scen. Endast läsning [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Returnerar:**
int

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

En rotation definieras genom användning av en latitude-koordinat, en longitude-koordinat och en revolution kring axeln som latitude- och longitude-koordinaterna. Det första elementet i returradarrayen – latitude, det andra – longitude, det tredje – revolution.

**Returnerar:**
float[] - Rotationskoordinater som float[]