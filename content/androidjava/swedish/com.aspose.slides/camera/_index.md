---
title: Camera
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar kamera.
type: docs
url: /sv/com.aspose.slides/camera/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)
```
public final class Camera extends PVIObject implements ICamera
```

Representerar kamera.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | Kameratyp. |
| [setCameraType(int value)](#setCameraType-int-) | Kameratyp. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Kamera-FOV (0-180 grader, synfält). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Kamera-FOV (0-180 grader, synfält). |
| [getZoom()](#getZoom--) | Kamerazoom (positivt värde i procent). |
| [setZoom(float value)](#setZoom-float-) | Kamerazoom (positivt värde i procent). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | En rotation definieras genom användning av en latitudkoordinat, en longitudkoordinat och en revolution kring axeln som latitud- och longitudkoordinaterna. |
| [getRotation()](#getRotation--) | En rotation definieras genom användning av en latitudkoordinat, en longitudkoordinat och en revolution kring axeln som latitud- och longitudkoordinaterna. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Skrivskyddad long.

**Returnerar:**
long
### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```

Kameratyp. Läs/skriv [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Returnerar:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```

Kameratyp. Läs/skriv [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```

Kamera-FOV (0-180 grader, synfält). Läs/skriv float.

**Returnerar:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

Kamera-FOV (0-180 grader, synfält). Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public final float getZoom()
```

Kamerazoom (positivt värde i procent). Läs/skriv float.

**Returnerar:**
float
### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```

Kamerazoom (positivt värde i procent). Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

En rotation definieras genom användning av en latitudkoordinat, en longitudkoordinat och en revolution kring axeln som latitud- och longitudkoordinaterna. Om något av koordinatvärdena är Float.NaN är hela rotationen odefinierad.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

En rotation definieras genom användning av en latitudkoordinat, en longitudkoordinat och en revolution kring axeln som latitud- och longitudkoordinaterna. Första elementet i returarrayen – latitud, andra – longitud, tredje – revolution. Returnerar null om ingen rotation är definierad.

**Returnerar:**
float[]