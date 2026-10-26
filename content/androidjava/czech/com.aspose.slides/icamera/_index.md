---
title: ICamera
second_title: Aspose.Slides for Android via Java API Reference
description: Represents Camera.
type: docs
url: /cs/com.aspose.slides/icamera/
---```
public interface ICamera
```

Representuje kameru.
## Metody

| Metoda | Popis |
| --- | --- |
| [getCameraType()](#getCameraType--) | Typ kamery Čtení/Zápis [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | Typ kamery Čtení/Zápis [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Zorné pole kamery (0-180 deg, field of View) Čtení/Zápis float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Zorné pole kamery (0-180 deg, field of View) Čtení/Zápis float. |
| [getZoom()](#getZoom--) | Zoom kamery (positive value in percentage) Čtení/Zápis float. |
| [setZoom(float value)](#setZoom-float-) | Zoom kamery (positive value in percentage) Čtení/Zápis float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Rotace je definována pomocí souřadnice zeměpisné šířky, souřadnice zeměpisné délky a otáčení okolo osy jako souřadnice zeměpisné šířky a délky. |
| [getRotation()](#getRotation--) | Rotace je definována pomocí souřadnice zeměpisné šířky, souřadnice zeměpisné délky a otáčení okolo osy jako souřadnice zeměpisné šířky a délky. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Typ kamery Čtení/Zápis [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Vrací:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

Typ kamery Čtení/Zápis [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

Zorné pole kamery (0-180 deg, field of View) Čtení/Zápis float.

**Vrací:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

Zorné pole kamery (0-180 deg, field of View) Čtení/Zápis float.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Zoom kamery (positive value in percentage) Čtení/Zápis float.

**Vrací:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

Zoom kamery (positive value in percentage) Čtení/Zápis float.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Rotace je definována pomocí souřadnice zeměpisné šířky, souřadnice zeměpisné délky a otáčení okolo osy jako souřadnice zeměpisné šířky a délky. Pokud je jakákoli hodnota souřadnice Float.NaN, je celá rotace nedefinovaná.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| latitude | float | Latitude value float |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Rotace je definována pomocí souřadnice zeměpisné šířky, souřadnice zeměpisné délky a otáčení okolo osy jako souřadnice zeměpisné šířky a délky. první prvek v návratovém poli – latitude, druhý – longitude, třetí – revolution. Vrací null, pokud není rotace definována.

**Vrací:**
float[] - Array of rotation values as float[].