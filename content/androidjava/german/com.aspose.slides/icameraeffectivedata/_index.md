---
title: ICameraEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective camera properties.
type: docs
url: /de/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

Unveränderliches Objekt, das wirksame Kameraeigenschaften enthält.

--------------------

Dieses Interface wird als Teil von [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) verwendet.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCameraType()](#getCameraType--) | Kameratyp. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Kamera-FOV (0-180 Grad, Sichtfeld). |
| [getZoom()](#getZoom--) | Kamera-Zoom (positiver Wert in Prozent). |
| [getRotation()](#getRotation--) | Eine Rotation wird durch die Verwendung einer Breitengradkoordinate, einer Längengradkoordinate und einer Drehung um die Achse definiert, wobei die Breitengrad- und Längengradkoordinaten verwendet werden. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


Kameratyp. Nur lesbar [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Rückgabe:**
int
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


Kamera-FOV (0-180 Grad, Sichtfeld). Nur lesbar float.

**Rückgabe:**
float
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


Kamera-Zoom (positiver Wert in Prozent). Nur lesbar float.

**Rückgabe:**
float
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Eine Rotation wird durch die Verwendung einer Breitengradkoordinate, einer Längengradkoordinate und einer Drehung um die Achse definiert, wobei die Breitengrad- und Längengradkoordinaten verwendet werden. Erstes Element im Rückgabe-Array – Breitengrad, zweites – Längengrad, drittes – Drehung. Gibt null zurück, wenn keine Rotation definiert ist. Nur lesbar float[].

**Rückgabe:**
float[] - Array von Rotationswerten als float[].