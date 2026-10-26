---
title: LightRig
second_title: Aspose.Slides Java API referencia
description: A LightRig-et ábrázolja.
type: docs
url: /hu/com.aspose.slides/lightrig/
---
**Inheritance:**
Öröklés: java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
Minden megvalósított interfész:
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

LightRig-et ábrázolja.
## Methods

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | Fény iránya. |
| [setDirection(int value)](#setDirection-int-) | Fény iránya. |
| [getLightType()](#getLightType--) | Egy előre beállított jobb fényt ábrázol, amely alakzatra alkalmazható. |
| [setLightType(int value)](#setLightType-int-) | Egy előre beállított jobb fényt ábrázol, amely alakzatra alkalmazható. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | A forgást a szélességi és hosszúsági koordináta, valamint a tengely körüli forogás definiálja. |
| [getRotation()](#getRotation--) | A forgást a szélességi és hosszúsági koordináta, valamint a tengely körüli forogás definiálja. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Returns:**
Visszatér:
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```

Fény iránya. Olvasás/írás [LightingDirection](../../com.aspose.slides/lightingdirection).

**Returns:**
Visszatér:
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```

Fény iránya. Olvasás/írás [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public final int getLightType()
```

Egy előre beállított jobb fényt ábrázol, amely alakzatra alkalmazható. A light rig egy csoport fényt ábrázol, amely meghatározott módon van elrendezve egy 3D jelenethez képest. Olvasás/írás [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Returns:**
Visszatér:
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

Egy előre beállított jobb fényt ábrázol, amely alakzatra alkalmazható. A light rig egy csoport fényt ábrázol, amely meghatározott módon van elrendezve egy 3D jelenethez képest. Olvasás/írás [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

A forgást a szélességi és hosszúsági koordináta, valamint a tengely körüli forogás definiálja. Ha bármely koordinátával kapcsolatos érték Float.NaN, a forgás nincs definiálva.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

A forgást a szélességi és hosszúsági koordináta, valamint a tengely körüli forogás definiálja. Az visszatérő tömb első eleme – szélesség, második – hosszúság, harmadik – forogás. Null értéket ad vissza, ha nincs definiált forgás.

**Returns:**
Visszatér:
float[]