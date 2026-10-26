---
title: ICameraEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective camera properties.
type: docs
url: /nl/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

Onveranderlijk object dat effectieve camera-eigenschappen bevat.

--------------------

Deze interface wordt gebruikt als onderdeel van [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Methoden

| Method | Description |
| --- | --- |
| [getCameraType()](#getCameraType--) | Cameratype. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180 graden, gezichtsveld). |
| [getZoom()](#getZoom--) | Camera-zoom (positieve waarde in percentage). |
| [getRotation()](#getRotation--) | Een rotatie wordt gedefinieerd door het gebruik van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een revolutie rond de as zoals de breedte- en lengtegradencoördinaten. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


Cameratype. Alleen-lezen [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Returns:**
int
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


Camera FOV (0-180 graden, gezichtsveld). Alleen-lezen float.

**Returns:**
float
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


Camera-zoom (positieve waarde in percentage). Alleen-lezen float.

**Returns:**
float
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Een rotatie wordt gedefinieerd door het gebruik van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een revolutie rond de as zoals de breedte- en lengtegradencoördinaten. eerste element in terugkeer-array – breedtegraad, tweede – lengtegraad, derde – revolutie. Retourneert null als geen rotatie gedefinieerd is.

**Returns:**
float[] - Array van rotatiewaarden als float[].