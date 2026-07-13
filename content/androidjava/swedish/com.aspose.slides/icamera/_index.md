---
title: ICamera
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar kamera.
type: docs
url: /sv/com.aspose.slides/icamera/
---```
public interface ICamera
```

Representerar kamera.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCameraType()](#getCameraType--) | Kameratyp Läs/skriv [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | Kameratyp Läs/skriv [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Kamera FOV (0-180 grad, synfält) Läs/skriv float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Kamera FOV (0-180 grad, synfält) Läs/skriv float. |
| [getZoom()](#getZoom--) | Kamera zoom (positivt värde i procent) Läs/skriv float. |
| [setZoom(float value)](#setZoom-float-) | Kamera zoom (positivt värde i procent) Läs/skriv float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | En rotation definieras genom användning av en latitudkoordinat, en longitudkoordinat och en revolution kring axeln som latitud- och longitudkoordinaterna. |
| [getRotation()](#getRotation--) | En rotation definieras genom användning av en latitudkoordinat, en longitudkoordinat och en revolution kring axeln som latitud- och longitudkoordinaterna. |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Kamerateyp Läs/skriv [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Returnerar:**
int

### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

Kamerateyp Läs/skriv [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

Kamera FOV (0-180 grad, synfält) Läs/skriv float.

**Returnerar:**
float

### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

Kamera FOV (0-180 grad, synfält) Läs/skriv float.

**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Kamera zoom (positivt värde i procent) Läs/skriv float.

**Returnerar:**
float

### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

Kamera zoom (positivt värde i procent) Läs/skriv float.

**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

En rotation definieras genom användning av en latitudkoordinat, en longitudkoordinat och en revolution kring axeln som latitud- och longitudkoordinaterna. Om något av koordinatvärdena är Float.NaN är all rotation odefinierad.

**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| latitude | float | Latitudvärde float |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

En rotation definieras genom användning av en latitudkoordinat, en longitudkoordinat och en revolution kring axeln som latitud- och longitudkoordinaterna. första element i returarrayen - latitud, andra - longitud, tredje - revolution. Returnerar null om ingen rotation är definierad.

**Returnerar:**
float[] - Array av rotationsvärden som float[].