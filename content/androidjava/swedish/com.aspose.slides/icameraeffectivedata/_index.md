---
title: ICameraEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective camera properties.
type: docs
url: /sv/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

Oföränderligt objekt som innehåller effektiva kameraegenskaper.

--------------------

Detta gränssnitt används som en del av [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCameraType()](#getCameraType--) | Kameratyp. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Kameras FOV (0-180 grader, synfält). |
| [getZoom()](#getZoom--) | Kamerans zoom (positivt värde i procent). |
| [getRotation()](#getRotation--) | En rotation definieras genom användning av en latitudkoordinat, en longitudkoordinat och en rotation kring axeln som latitud- och longitudkoordinaterna. |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Kameratyp. Skrivskyddad [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Returnerar:**
int

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

Kameras FOV (0-180 grader, synfält). Skrivskyddad float.

**Returnerar:**
float

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Kamerans zoom (positivt värde i procent). Skrivskyddad float.

**Returnerar:**
float

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

En rotation definieras genom användning av en latitudkoordinat, en longitudkoordinat och en rotation kring axeln som latitud- och longitudkoordinaterna. första elementet i returarrayen - latitud, andra - longitud, tredje - rotation. Returnerar null om ingen rotation är definierad.

**Returnerar:**
float[] - Array av rotationsvärden som float[].