---
title: ICamera
second_title: Aspose.Slides for Android via Java API Reference
description: Represents Camera.
type: docs
url: /nl/com.aspose.slides/icamera/
---```
public interface ICamera
```

Represents Camera.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCameraType()](#getCameraType--) | Cameratype Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | Cameratype Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180 deg, gezichtsveld) Read/write float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Camera FOV (0-180 deg, gezichtsveld) Read/write float. |
| [getZoom()](#getZoom--) | Camera-zoom (positieve waarde in percentage) Read/write float. |
| [setZoom(float value)](#setZoom-float-) | Camera-zoom (positieve waarde in percentage) Read/write float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Een rotatie wordt gedefinieerd door het gebruik van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een omwenteling rondom de as als de breedte- en lengtegraadcoördinaten. |
| [getRotation()](#getRotation--) | Een rotatie wordt gedefinieerd door het gebruik van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een omwenteling rondom de as als de breedte- en lengtegraadcoördinaten. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


Cameratype Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Retourwaarde:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```


Cameratype Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


Camera FOV (0-180 deg, gezichtsveld) Read/write float.

**Retourwaarde:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```


Camera FOV (0-180 deg, gezichtsveld) Read/write float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


Camera-zoom (positieve waarde in percentage) Read/write float.

**Retourwaarde:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```


Camera-zoom (positieve waarde in percentage) Read/write float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```


Een rotatie wordt gedefinieerd door het gebruik van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een omwenteling rondom de as als de breedte- en lengtegraadcoördinaten. Als een van de coördinaatwaarden Float.NaN is, is de rotatie ongedefinieerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| latitude | float | Breedtegraadwaarde float |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Een rotatie wordt gedefinieerd door het gebruik van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een omwenteling rondom de as als de breedte- en lengtegraadcoördinaten. eerste element in het geretourneerde array – breedtegraad, tweede – lengtegraad, derde – omwenteling. Retourneert null als geen rotatie is gedefinieerd.

**Retourwaarde:**
float[] - Array van rotatiewaarden als float[].