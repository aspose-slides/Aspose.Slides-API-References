---
title: Camera
second_title: Aspose.Slides dla Java Referencja API
description: Reprezentuje kamerę.
type: docs
url: /pl/com.aspose.slides/camera/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)
```
public final class Camera extends PVIObject implements ICamera
```

Reprezentuje kamerę.
## Metody

| Metoda | Opis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | Typ kamery. |
| [setCameraType(int value)](#setCameraType-int-) | Typ kamery. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Pole widzenia kamery (0-180 deg, field of View). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Pole widzenia kamery (0-180 deg, field of View). |
| [getZoom()](#getZoom--) | Zoom kamery (wartość dodatnia w procentach). |
| [setZoom(float value)](#setZoom-float-) | Zoom kamery (wartość dodatnia w procentach). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Rotacja jest definiowana przy użyciu współrzędnej szerokości, współrzędnej długości oraz obrotu wokół osi jako współrzędne szerokości i długości. |
| [getRotation()](#getRotation--) | Rotacja jest definiowana przy użyciu współrzędnej szerokości, współrzędnej długości oraz obrotu wokół osi jako współrzędne szerokości i długości. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Wersja. Tylko do odczytu long.

**Zwraca:**
long
### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```


Typ kamery. Odczyt/zapis [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Zwraca:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```


Typ kamery. Odczyt/zapis [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```


Pole widzenia kamery (0-180 deg, field of View). Odczyt/zapis float.

**Zwraca:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```


Pole widzenia kamery (0-180 deg, field of View). Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public final float getZoom()
```


Zoom kamery (wartość dodatnia w procentach). Odczyt/zapis float.

**Zwraca:**
float
### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```


Zoom kamery (wartość dodatnia w procentach). Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```


Rotacja jest definiowana przy użyciu współrzędnej szerokości, współrzędnej długości oraz obrotu wokół osi jako współrzędne szerokości i długości. Jeśli dowolna wartość współrzędnej jest Float.NaN, cała rotacja jest nieokreślona.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public final float[] getRotation()
```


Rotacja jest definiowana przy użyciu współrzędnej szerokości, współrzędnej długości oraz obrotu wokół osi jako współrzędne szerokości i długości. pierwszy element w zwracanej tablicy – szerokość, drugi – długość, trzeci – obrót. Zwraca null, jeśli nie zdefiniowano rotacji.

**Zwraca:**
float[]