---
title: ICamera
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt Kamera dar.
type: docs
url: /de/com.aspose.slides/icamera/
---```
public interface ICamera
```

Stellt Kamera dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCameraType()](#getCameraType--) | Kamera-Typ Lesen/Schreiben [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | Kamera-Typ Lesen/Schreiben [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Kamera-FOV (0-180 Grad, Sichtfeld) Lesen/Schreiben float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Kamera-FOV (0-180 Grad, Sichtfeld) Lesen/Schreiben float. |
| [getZoom()](#getZoom--) | Kamera-Zoom (positiver Wert in Prozent) Lesen/Schreiben float. |
| [setZoom(float value)](#setZoom-float-) | Kamera-Zoom (positiver Wert in Prozent) Lesen/Schreiben float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Eine Rotation wird durch die Verwendung einer Breitengradkoordinate, einer Längengradkoordinate und einer Umdrehung um die Achse definiert, wobei die Breitengrad- und Längengradkoordinaten verwendet werden. |
| [getRotation()](#getRotation--) | Eine Rotation wird durch die Verwendung einer Breitengradkoordinate, einer Längengradkoordinate und einer Umdrehung um die Achse definiert, wobei die Breitengrad- und Längengradkoordinaten verwendet werden. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Kamera-Typ Lesen/Schreiben [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Rückgabe:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

Kamera-Typ Lesen/Schreiben [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

Kamera-FOV (0-180 Grad, Sichtfeld) Lesen/Schreiben float.

**Rückgabe:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

Kamera-FOV (0-180 Grad, Sichtfeld) Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Kamera-Zoom (positiver Wert in Prozent) Lesen/Schreiben float.

**Rückgabe:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

Kamera-Zoom (positiver Wert in Prozent) Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Eine Rotation wird durch die Verwendung einer Breitengradkoordinate, einer Längengradkoordinate und einer Umdrehung um die Achse definiert, wobei die Breitengrad- und Längengradkoordinaten verwendet werden. Wenn ein Koordinatenwert Float.NaN ist, ist die gesamte Rotation undefiniert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| latitude | float | Breitengradwert float |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Eine Rotation wird durch die Verwendung einer Breitengradkoordinate, einer Längengradkoordinate und einer Umdrehung um die Achse definiert, wobei die Breitengrad- und Längengradkoordinaten verwendet werden. Erstes Element im Rückgabe-Array – Breitengrad, zweites – Längengrad, drittes – Umdrehung. Gibt null zurück, wenn keine Rotation definiert ist.

**Rückgabe:**
float[] – Array von Rotationswerten als float[].