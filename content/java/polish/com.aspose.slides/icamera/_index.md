---
title: ICamera
second_title: Aspose.Slides dla Java API Reference
description: Reprezentuje kamerę.
type: docs
url: /pl/com.aspose.slides/icamera/
---```
public interface ICamera
```

Reprezentuje kamerę.
## Metody

| Method | Description |
| --- | --- |
| [getCameraType()](#getCameraType--) | Typ kamery Odczyt/zapis [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | Typ kamery Odczyt/zapis [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Kąt widzenia kamery (0-180 deg, field of View) Odczyt/zapis float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Kąt widzenia kamery (0-180 deg, field of View) Odczyt/zapis float. |
| [getZoom()](#getZoom--) | Powiększenie kamery (positive value in percentage) Odczyt/zapis float. |
| [setZoom(float value)](#setZoom-float-) | Powiększenie kamery (positive value in percentage) Odczyt/zapis float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Rotacja jest definiowana przy użyciu współrzędnej szerokości, współrzędnej długości i obrotu wokół osi jako współrzędnych szerokości i długości. |
| [getRotation()](#getRotation--) | Rotacja jest definiowana przy użyciu współrzędnej szerokości, współrzędnej długości i obrotu wokół osi jako współrzędnych szerokości i długości. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


Typ kamery Odczyt/zapis [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Zwraca:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```


Typ kamery Odczyt/zapis [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


Kąt widzenia kamery (0-180 deg, field of View) Odczyt/zapis float.

**Zwraca:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```


Kąt widzenia kamery (0-180 deg, field of View) Odczyt/zapis float.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


Powiększenie kamery (positive value in percentage) Odczyt/zapis float.

**Zwraca:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```


Powiększenie kamery (positive value in percentage) Odczyt/zapis float.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```


Rotacja jest definiowana przy użyciu współrzędnej szerokości, współrzędnej długości i obrotu wokół osi jako współrzędnych szerokości i długości. Jeśli dowolna wartość współrzędnej jest Float.NaN, cała rotacja jest nieokreślona.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| latitude | float | Wartość szerokości float |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Rotacja jest definiowana przy użyciu współrzędnej szerokości, współrzędnej długości i obrotu wokół osi jako współrzędnych szerokości i długości. pierwszy element zwracanej tablicy – szerokość, drugi – długość, trzeci – obrót. Zwraca null, jeśli rotacja nie jest określona.

**Zwraca:**
float[] - Tablica wartości rotacji jako float[].