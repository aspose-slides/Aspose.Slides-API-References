---
title: Camera
second_title: Aspose.Slides voor Java API-referentie
description: Representeert Camera.
type: docs
url: /nl/com.aspose.slides/camera/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)
```
public final class Camera extends PVIObject implements ICamera
```

Representeert Camera.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | Cameratype. |
| [setCameraType(int value)](#setCameraType-int-) | Cameratype. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180 graden, gezichtsveld). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Camera FOV (0-180 graden, gezichtsveld). |
| [getZoom()](#getZoom--) | Camera zoom (positieve waarde in percentage). |
| [setZoom(float value)](#setZoom-float-) | Camera zoom (positieve waarde in percentage). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Een rotatie wordt gedefinieerd door het gebruik van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een rotatie rond de as als de breedte- en lengtegraadcoördinaten. |
| [getRotation()](#getRotation--) | Een rotatie wordt gedefinieerd door het gebruik van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een rotatie rond de as als de breedte- en lengtegraadcoördinaten. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versie. Alleen-lezen long.

**Retour:**
long
### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```


Cameratype. Lezen/schrijven [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Retour:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```


Cameratype. Lezen/schrijven [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```


Camera FOV (0-180 graden, gezichtsveld). Lezen/schrijven float.

**Retour:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```


Camera FOV (0-180 graden, gezichtsveld). Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public final float getZoom()
```


Camera zoom (positieve waarde in percentage). Lezen/schrijven float.

**Retour:**
float
### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```


Camera zoom (positieve waarde in percentage). Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```


Een rotatie wordt gedefinieerd door het gebruik van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een rotatie rond de as als de breedte- en lengtegraadcoördinaten. Als een van de coördinaatwaarden Float.NaN is, is de volledige rotatie ongedefinieerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public final float[] getRotation()
```


Een rotatie wordt gedefinieerd door het gebruik van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een rotatie rond de as als de breedte- en lengtegraadcoördinaten. eerste element in teruggegeven array - breedtegraad, tweede - lengtegraad, derde - rotatie. Retourneert null als geen rotatie gedefinieerd is.

**Retour:**
float[]