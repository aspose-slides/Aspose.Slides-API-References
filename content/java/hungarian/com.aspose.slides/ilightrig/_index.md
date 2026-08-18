---
title: ILightRig
second_title: Aspose.Slides for Java API Reference
description: Represents LightRig.
type: docs
url: /hu/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

Representálja a LightRig-et.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getDirection()](#getDirection--) | Fény iránya. |
| [setDirection(int value)](#setDirection-int-) | Fény iránya. |
| [getLightType()](#getLightType--) | Egy előre beállított jobb fényt reprezentál, amely egy alakzatra alkalmazható. |
| [setLightType(int value)](#setLightType-int-) | Egy előre beállított jobb fényt reprezentál, amely egy alakzatra alkalmazható. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Egy forgatás latitude, longitude koordináták és a tengely körüli forogás használatával van definiálva. |
| [getRotation()](#getRotation--) | Egy forgatás latitude, longitude koordináták és a tengely körüli forogás használatával van definiálva. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Fény iránya. Olvasás/írás [LightingDirection](../../com.aspose.slides/lightingdirection).

**Visszatérési érték:**
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

Egy előre beállított jobb fényt reprezentál, amely egy alakzatra alkalmazható. A light rig egy olyan fénycsoportot képviseli, amely meghatározott módon van elrendezve egy 3D-s jelenethez képest. Olvasás/írás [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Visszatérési érték:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

Egy előre beállított jobb fényt reprezentál, amely egy alakzatra alkalmazható. A light rig egy olyan fénycsoportot képviseli, amely meghatározott módon van elrendezve egy 3D-s jelenethez képest. Olvasás/írás [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Egy forgatás latitude, longitude koordináták és a tengely körüli forogás használatával van definiálva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| latitude | float | Latitude koordináta |
| longitude | float | Longitude koordináta |
| revolution | float | Revolution koordináta |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Egy forgatás latitude, longitude koordináták és a tengely körüli forogás használatával van definiálva. Az első elem a visszatérő tömbben – latitude, a második – longitude, a harmadik – revolution.

**Visszatérési érték:**
float[] - Forgatási koordináták float[]-ként