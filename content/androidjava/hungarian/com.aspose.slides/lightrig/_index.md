---
title: LightRig
second_title: Aspose.Slides Androidra a Java API hivatkozás
description: A LightRig-et reprezentálja.
type: docs
url: /hu/com.aspose.slides/lightrig/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden megvalósított interfész:**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

A LightRig-et reprezentálja.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | Fény irány. |
| [setDirection(int value)](#setDirection-int-) | Fény irány. |
| [getLightType()](#getLightType--) | Egy előre beállított fény jobb, amely alkalmazható egy alakzatra. |
| [setLightType(int value)](#setLightType-int-) | Egy előre beállított fény jobb, amely alkalmazható egy alakzatra. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | A forgást a szélességi koordináta, a hosszúsági koordináta és a tengely körüli revolúció segítségével definiálják, mint szélességi és hosszúsági koordinátákat. |
| [getRotation()](#getRotation--) | A forgást a szélességi koordináta, a hosszúsági koordináta és a tengely körüli revolúció segítségével definiálják, mint szélességi és hosszúsági koordinátákat. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszatér:**  
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```

Fény irány. Olvasás/írás [LightingDirection](../../com.aspose.slides/lightingdirection).

**Visszatér:**  
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```

Fény irány. Olvasás/írás [LightingDirection](../../com.aspose.slides/lightingdirection).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public final int getLightType()
```

Egy előre beállított fény jobb, amely alkalmazható egy alakzatra. A light rig egy csoport fényt reprezentál, amely egy adott módon van orientálva egy 3D jelenethez képest. Olvasás/írás [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Visszatér:**  
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

Egy előre beállított fény jobb, amely alkalmazható egy alakzatra. A light rig egy csoport fényt reprezentál, amely egy adott módon van orientálva egy 3D jelenethez képest. Olvasás/írás [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

A forgást a szélességi koordináta, a hosszúsági koordináta és a tengely körüli revolúció segítségével definiálják, mint szélességi és hosszúsági koordinátákat. Ha bármely koordinát értéke Float.NaN, a forgás teljes egészében nincs definiálva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

A forgást a szélességi koordináta, a hosszúsági koordináta és a tengely körüli revolúció segítségével definiálják, mint szélességi és hosszúsági koordinátákat. Az első elem a visszatérő tömbben – szélesség, a második – hosszúság, a harmadik – revolúció. Null értéket ad vissza, ha nincs definiált forgás.

**Visszatér:**  
float[]