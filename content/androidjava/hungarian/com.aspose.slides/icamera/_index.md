---
title: ICamera
second_title: Aspose.Slides for Android via Java API Reference
description: Represents Camera.
type: docs
url: /hu/com.aspose.slides/icamera/
---```
public interface ICamera
```

Képviseli a Camera-t.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getCameraType()](#getCameraType--) | Camera típus Olvasás/írás [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | Camera típus Olvasás/írás [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180 deg, látómező) Olvasás/írás float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Camera FOV (0-180 deg, látómező) Olvasás/írás float. |
| [getZoom()](#getZoom--) | Camera zoom (pozitív érték százalékban) Olvasás/írás float. |
| [setZoom(float value)](#setZoom-float-) | Camera zoom (pozitív érték százalékban) Olvasás/írás float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Az elfordulás a latitude koordináta, a longitude koordináta és a revolution használatával van definiálva, mint a latitude és longitude koordináták. |
| [getRotation()](#getRotation--) | Az elfordulás a latitude koordináta, a longitude koordináta és a revolution használatával van definiálva, mint a latitude és longitude koordináták. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Camera típus Olvasás/írás [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Visszatér:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

Camera típus Olvasás/írás [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

Camera FOV (0-180 deg, látómező) Olvasás/írás float.

**Visszatér:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

Camera FOV (0-180 deg, látómező) Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Camera zoom (pozitív érték százalékban) Olvasás/írás float.

**Visszatér:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

Camera zoom (pozitív érték százalékban) Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Az elfordulás a latitude koordináta, a longitude koordináta és a revolution használatával van definiálva, mint a latitude és longitude koordináták. Ha bármely koordináta értéke Float.NaN, az összes elfordulás nincs definiálva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| latitude | float | latitude érték float |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Az elfordulás a latitude koordináta, a longitude koordináta és a revolution használatával van definiálva. Az első elem a visszatérő tömbben – latitude, a második – longitude, a harmadik – revolution. Null értéket ad vissza, ha nincs elfordulás definiálva.

**Visszatér:**
float[] - Az elfordulás értékeinek tömbje float[].