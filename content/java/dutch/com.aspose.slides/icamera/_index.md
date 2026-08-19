---
title: ICamera
second_title: Aspose.Slides for Java API Reference
description: Vertegenwoordigt Camera.
type: docs
url: /nl/com.aspose.slides/icamera/
---```
public interface ICamera
```

Vertegenwoordigt Camera.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCameraType()](#getCameraType--) | Cameratype Lezen/Schrijven [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | Cameratype Lezen/Schrijven [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180 graden, gezichtsveld) Lezen/Schrijven float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Camera FOV (0-180 graden, gezichtsveld) Lezen/Schrijven float. |
| [getZoom()](#getZoom--) | Camerazoom (positieve waarde in percentage) Lezen/Schrijven float. |
| [setZoom(float value)](#setZoom-float-) | Camerazoom (positieve waarde in percentage) Lezen/Schrijven float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Een rotatie wordt gedefinieerd door het gebruik van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een revolutie rond de as als de breedtegraad- en lengtegraatcoördinaten. |
| [getRotation()](#getRotation--) | Een rotatie wordt gedefinieerd door het gebruik van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een revolutie rond de as als de breedtegraad- en lengtegraatcoördinaten. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


Cameratype Lezen/Schrijven [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Retour:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```


Cameratype Lezen/Schrijven [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


Camera FOV (0-180 graden, gezichtsveld) Lezen/Schrijven float.

**Retour:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```


Camera FOV (0-180 graden, gezichtsveld) Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


Camerazoom (positieve waarde in percentage) Lezen/Schrijven float.

**Retour:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```


Camerazoom (positieve waarde in percentage) Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```


Een rotatie wordt gedefinieerd door het gebruik van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een revolutie rond de as als de breedtegraad- en lengtegraatcoördinaten. Als een van de coördinaatwaarden Float.NaN is, is alle rotatie ongedefinieerd.

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


Een rotatie wordt gedefinieerd door het gebruik van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een revolutie rond de as als de breedtegraad- en lengtegraatcoördinaten. eerste element in teruggegeven array - breedtegraad, tweede - lengtegraad, derde - revolutie. Retourneert null als er geen rotatie gedefinieerd is.

**Retour:**
float[] - Array van rotatiewaarden als float[].