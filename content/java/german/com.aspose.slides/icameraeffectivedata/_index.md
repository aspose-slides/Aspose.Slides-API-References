---
title: ICameraEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective camera properties.
type: docs
url: /de/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

Unveränderliches Objekt, das effektive Kameraeigenschaften enthält.

--------------------

Dieses Interface wird als Teil von [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) verwendet.
## Methoden

| Method | Description |
| --- | --- |
| [getCameraType()](#getCameraType--) | Kameratyp. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Kamera-FOV (0-180 Grad, Sichtfeld). |
| [getZoom()](#getZoom--) | Kamera-Zoom (positiver Wert in Prozent). |
| [getRotation()](#getRotation--) | Eine Rotation ist definiert durch die Verwendung einer Breitengrad-Koordinate, einer Längengrad-Koordinate und einer Drehung um die Achse als Breitengrad- und Längengrad-Koordinate. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


Kameratyp. Nur lesend [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Rückgabe:**
int
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


Kamera-FOV (0-180 Grad, Sichtfeld). Nur lesend float.

**Rückgabe:**
float
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


Kamera-Zoom (positiver Wert in Prozent). Nur lesend float.

**Rückgabe:**
float
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Eine Rotation ist definiert durch die Verwendung einer Breitengrad-Koordinate, einer Längengrad-Koordinate und einer Drehung um die Achse als Breitengrad- und Längengrad-Koordinate. Erstes Element im Rückgabe-Array – Breitengrad, zweites – Längengrad, drittes – Drehung. Gibt null zurück, wenn keine Rotation definiert ist.

**Rückgabe:**
float[] - Array von Rotationswerten als float[].