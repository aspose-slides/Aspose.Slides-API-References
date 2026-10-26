---
title: ICamera
second_title: Aspose.Slides for Android via Java API Reference
description: Represents Camera.
type: docs
url: /pl/com.aspose.slides/icamera/
---```
public interface ICamera
```

Reprezentuje Camera.

## Metody

| Metoda | Opis |
| --- | --- |
| [getCameraType()](#getCameraType--) | Camera type Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | Camera type Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180 deg, field of View) Read/write float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Camera FOV (0-180 deg, field of View) Read/write float. |
| [getZoom()](#getZoom--) | Camera zoom (positive value in percentage) Read/write float. |
| [setZoom(float value)](#setZoom-float-) | Camera zoom (positive value in percentage) Read/write float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |
| [getRotation()](#getRotation--) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Typ kamery odczyt/zapis [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Zwraca:**
int

### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

Typ kamery odczyt/zapis [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

Kąt widzenia kamery (0-180 deg, field of View) odczyt/zapis float.

**Zwraca:**
float

### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

Kąt widzenia kamery (0-180 deg, field of View) odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Powiększenie kamery (positive value in percentage) odczyt/zapis float.

**Zwraca:**
float

### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

Powiększenie kamery (positive value in percentage) odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Rotacja jest definiowana przy użyciu współrzędnej szerokości, współrzędnej długości oraz obrotu wokół osi jako współrzędnych szerokości i długości. Jeśli którakolwiek wartość współrzędnej jest Float.NaN, cała rotacja jest niezdefiniowana.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| latitude | float | Wartość szerokości typu float |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Rotacja jest definiowana przy użyciu współrzędnej szerokości, współrzędnej długości oraz obrotu wokół osi jako współrzędnych szerokości i długości. pierwszy element w zwracanej tablicy - szerokość, drugi - długość, trzeci - obrót. Zwraca null, jeśli rotacja nie jest zdefiniowana.

**Zwraca:**
float[] - Tablica wartości rotacji jako float[].