---
title: ILightRig
second_title: Aspose.Slides for Android Java API hivatkozás
description: A LightRig-et képviseli.
type: docs
url: /hu/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

A LightRig-et képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getDirection()](#getDirection--) | Light direction. |
| [setDirection(int value)](#setDirection-int-) | Light direction. |
| [getLightType()](#getLightType--) | Represents a preset light right that can be applied to a shape. |
| [setLightType(int value)](#setLightType-int-) | Represents a preset light right that can be applied to a shape. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |
| [getRotation()](#getRotation--) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Fény iránya. Olvasás/írás [LightingDirection](../../com.aspose.slides/lightingdirection).

**Visszatér:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Fény iránya. Olvasás/írás [LightingDirection](../../com.aspose.slides/lightingdirection).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Egy előre beállított jobb fényt képvisel, amely egy alakzatra alkalmazható. A light rig egy csoport fényt képvisel, amelyek specifikus módon vannak orientálva egy 3D jelenethez képest. Olvasás/írás [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Visszatér:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

Egy előre beállított jobb fényt képvisel, amely egy alakzatra alkalmazható. A light rig egy csoport fényt képvisel, amelyek specifikus módon vannak orientálva egy 3D jelenethez képest. Olvasás/írás [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

A forgatás a szélességi koordináta, a hosszúsági koordináta és egy tengely körüli fordulat használatával definiálható, mint a szélességi és hosszúsági koordináták.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| latitude | float | Szélességi koordináta float |
| longitude | float | Hosszúsági koordináta float |
| revolution | float | Fordulat koordináta float |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

A forgatás a szélességi koordináta, a hosszúsági koordináta és egy tengely körüli fordulat használatával definiálható, mint a szélességi és hosszúsági koordináták. az első elem a visszatérő tömbben - latitude, a második - longitude, a harmadik - revolution.

**Visszatér:**
float[] - Forgatási koordináták float[] formában