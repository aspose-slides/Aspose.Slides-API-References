---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Módosíthatatlan objektum, amely a hatékony fényrendszer tulajdonságait tartalmazza.
type: docs
url: /hu/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Módosíthatatlan objektum, amely a hatékony fényrendszer tulajdonságait tartalmazza.

--------------------

Ez a felület a [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) részeként használatos.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getDirection()](#getDirection--) | Fény iránya. |
| [getLightType()](#getLightType--) | Egy előre beállított fényirányt képvisel, amely egy alakra alkalmazható. |
| [getRotation()](#getRotation--) | A forgatás a szélességi koordináta, a hosszúsági koordináta és a tengely körüli forogás használatával van definiálva, mint a szélességi és hosszúsági koordináták. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Fény iránya. Csak olvasható [LightingDirection](../../com.aspose.slides/lightingdirection).

**Visszatér:**
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Egy előre beállított fényirányt reprezentál, amely egy alakra alkalmazható. A fényrendszer egy csoportra utal, amely meghatározott módon van elrendezve egy 3D jelenethez képest. Csak olvasható [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Visszatér:**
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

A forgatás a szélességi koordináta, a hosszúsági koordináta és a tengely körüli forogás használatával van definiálva, mint a szélességi és hosszúsági koordináták. Az eredmény tömb első eleme – szélesség, a második – hosszúság, a harmadik – forogás.

**Visszatér:**
float[] - Rotációs koordináták float[]