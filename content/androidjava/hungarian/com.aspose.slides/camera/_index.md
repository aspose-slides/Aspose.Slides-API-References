---
title: Camera
second_title: Aspose.Slides Androidra Java API hivatkozás segítségével
description: Kamera reprezentációja.
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

Képviseli a Camera-t.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | Kamera típusa. |
| [setCameraType(int value)](#setCameraType-int-) | Kamera típusa. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Kamera FOV (0-180 fok, látómező). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Kamera FOV (0-180 fok, látómező). |
| [getZoom()](#getZoom--) | Kamera zoom (pozitív érték százalékban). |
| [setZoom(float value)](#setZoom-float-) | Kamera zoom (pozitív érték százalékban). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | A forgást a szélességi, a hosszúsági koordináta és a tengely körüli fordulat határozza meg. |
| [getRotation()](#getRotation--) | A forgást a szélességi, a hosszúsági koordináta és a tengely körüli fordulat határozza meg. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszatérési érték:**  
long
### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```

Kamera típusa. Olvasás/írás [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Visszatérési érték:**  
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

Kamera FOV (0-180 fok, látómező). Olvasás/írás float.

**Visszatérési érték:**  
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

Kamera FOV (0-180 fok, látómező). Olvasás/írás float.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public final float getZoom()
```

Kamera zoom (pozitív érték százalékban). Olvasás/írás float.

**Visszatérési érték:**  
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

A forgást a szélességi, a hosszúsági koordináta és a tengely körüli fordulat határozza meg. Ha bármely koordináta értéke Float.NaN, a forgás meghatározatlan.

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

A forgást a szélességi, a hosszúsági koordináta és a tengely körüli fordulat határozza meg. Az eredmény tömb első eleme – szélességi, a második – hosszúsági, a harmadik – fordulat. Null értéket ad vissza, ha nincs definiált forgás.

**Visszatérési érték:**  
float[]