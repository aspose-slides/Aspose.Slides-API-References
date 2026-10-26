---
title: ICameraEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective camera properties.
type: docs
url: /el/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

Αμετάβλητο αντικείμενο που περιλαμβάνει τις ενεργές ιδιότητες της κάμερας.

--------------------

Αυτό το interface χρησιμοποιείται ως μέρος του [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Μεθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCameraType()](#getCameraType--) | Camera type. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180 deg, field of View). |
| [getZoom()](#getZoom--) | Camera zoom (positive value in percentage). |
| [getRotation()](#getRotation--) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


Camera type. Μόνο-ανάγνωση [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Επιστρέφει:**
int
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


Camera FOV (0-180 deg, field of View). Μόνο-ανάγνωση float.

**Επιστρέφει:**
float
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


Camera zoom (positive value in percentage). Μόνο-ανάγνωση float.

**Επιστρέφει:**
float
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. first element in return array - latitude, second - longitude, third - revolution. Returns null if no rotation defined.

**Επιστρέφει:**
float[] - Πίνακας τιμών περιστροφής ως float[].