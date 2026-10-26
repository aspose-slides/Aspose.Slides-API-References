---
title: Camera
second_title: Aspose.Slides a Java API referencia
description: Kamerát reprezentál.
type: docs
url: /hu/com.aspose.slides/camera/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden megvalósított interfész:**
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)
```
public final class Camera extends PVIObject implements ICamera
```

Kamerát reprezentál.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | Kamera típusa. |
| [setCameraType(int value)](#setCameraType-int-) | Kamera típusa. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Kamera FOV (0-180 fok, látótér). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Kamera FOV (0-180 fok, látótér). |
| [getZoom()](#getZoom--) | Kamera zoom (pozitív érték százalékban). |
| [setZoom(float value)](#setZoom-float-) | Kamera zoom (pozitív érték százalékban). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | A forgatás egy szélességi koordináta, egy hosszúsági koordináta és az ezekhez a koordinátákhoz tartozó tengely körüli forogás használatával van definiálva. |
| [getRotation()](#getRotation--) | A forgatás egy szélességi koordináta, egy hosszúsági koordináta és az ezekhez a koordinátákhoz tartozó tengely körüli forogás használatával van definiálva. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszatér:**  
long
### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```

Kamera típusa. Olvasás/írás [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Visszatér:**  
int
### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```

Kamera típusa. Olvasás/írás [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```

Kamera FOV (0-180 fok, látótér). Olvasás/írás float.

**Visszatér:**  
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

Kamera FOV (0-180 fok, látótér). Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public final float getZoom()
```

Kamera zoom (pozitív érték százalékban). Olvasás/írás float.

**Visszatér:**  
float
### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```

Kamera zoom (pozitív érték százalékban). Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

A forgatás egy szélességi koordináta, egy hosszúsági koordináta és az ezekhez a koordinátákhoz tartozó tengely körüli forogás használatával van definiálva. Ha bármely koordinátérték Float.NaN, a forgatás nem definiált.

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

A forgatás egy szélességi koordináta, egy hosszúsági koordináta és az ezekhez a koordinátákhoz tartozó tengely körüli forogás használatával van definiálva. az eredmény tömb első eleme – szélesség, a második – hosszúság, a harmadik – forogás. Nullt ad vissza, ha nincs forgatás definiálva.

**Visszatér:**  
float[]