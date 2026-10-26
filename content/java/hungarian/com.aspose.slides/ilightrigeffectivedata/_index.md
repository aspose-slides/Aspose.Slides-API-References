---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Megváltoztathatatlan objektum, amely a hatékony light rig tulajdonságait tartalmazza.
type: docs
url: /hu/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Megváltoztathatatlan objektum, amely tartalmazza a hatékony light rig tulajdonságokat.

--------------------

Ez az interfész a [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) részeként használatos.
## Methods

| Method | Description |
| --- | --- |
| [getDirection()](#getDirection--) | Fényirány. |
| [getLightType()](#getLightType--) | Előre beállított fény jobb oldalát reprezentálja, amely egy alakzatra alkalmazható. |
| [getRotation()](#getRotation--) | A forgatás egy szélességi koordináta, egy hosszúsági koordináta és a tengely körüli forradalom használatával van definiálva, mint a szélességi és hosszúsági koordináták. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Fényirány. Csak olvasható [LightingDirection](../../com.aspose.slides/lightingdirection).

**Returns:**
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Előre beállított fény jobb oldalát reprezentálja, amely egy alakzatra alkalmazható. A light rig egy olyan fénycsoportot képvisel, amely meghatározott módon helyezkedik el egy 3D-s jelenethez képest. Csak olvasható [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Returns:**
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

A forgatás egy szélességi koordináta, egy hosszúsági koordináta és a tengely körüli forradalom használatával van definiálva, mint a szélességi és hosszúsági koordináták. Az első elem a visszatérő tömbben – szélesség, a második – hosszúság, a harmadik – forradalom.

**Returns:**
float[] - Forgatási koordináták float[]