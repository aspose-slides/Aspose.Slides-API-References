---
title: ICamera
second_title: Aspose.Slides pro Java API Reference
description: Representuje kameru.
type: docs
url: /cs/com.aspose.slides/icamera/
---```
public interface ICamera
```

Representuje kameru.
## Metody

| Metoda | Popis |
| --- | --- |
| [getCameraType()](#getCameraType--) | Camera typ Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | Camera typ Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180 deg, zorné pole) Read/write float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Camera FOV (0-180 deg, zorné pole) Read/write float. |
| [getZoom()](#getZoom--) | Camera zoom (kladná hodnota v procentech) Read/write float. |
| [setZoom(float value)](#setZoom-float-) | Camera zoom (kladná hodnota v procentech) Read/write float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Rotace je definována pomocí souřadnice latitude, souřadnice longitude a otáčení (revolution) kolem osy jako souřadnic latitude a longitude. |
| [getRotation()](#getRotation--) | Rotace je definována pomocí souřadnice latitude, souřadnice longitude a otáčení (revolution) kolem osy jako souřadnic latitude a longitude. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Camera typ Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Vrací:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

Camera typ Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

Camera FOV (0-180 deg, zorné pole) Read/write float.

**Vrací:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

Camera FOV (0-180 deg, zorné pole) Read/write float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Camera zoom (kladná hodnota v procentech) Read/write float.

**Vrací:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

Camera zoom (kladná hodnota v procentech) Read/write float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Rotace je definována pomocí souřadnice latitude, souřadnice longitude a otáčení (revolution) kolem osy jako souřadnic latitude a longitude. Pokud je jakákoli hodnota souřadnice Float.NaN, je celá rotace nedefinována.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| latitude | float | Hodnota latitude float |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Rotace je definována pomocí souřadnice latitude, souřadnice longitude a otáčení (revolution) kolem osy jako souřadnic latitude a longitude. První prvek v návratovém poli – latitude, druhý – longitude, třetí – revolution. Vrátí null, pokud není definována žádná rotace.

**Vrací:**
float[] – pole hodnot rotace jako float[].