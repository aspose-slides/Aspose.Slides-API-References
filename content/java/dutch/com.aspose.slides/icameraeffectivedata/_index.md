---
title: ICameraEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Onveranderlijk object dat effectieve camera-eigenschappen bevat.
type: docs
url: /nl/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

Onveranderlijk object dat effectieve camera-eigenschappen bevat.

--------------------

Deze interface wordt gebruikt als onderdeel van [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCameraType()](#getCameraType--) | Cameratype. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180 graden, gezichtsveld). |
| [getZoom()](#getZoom--) | Camera-zoom (positieve waarde in procenten). |
| [getRotation()](#getRotation--) | Een rotatie wordt gedefinieerd door het gebruik van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een omwenteling rond de as als de breedtegraad- en lengtegraadcoördinaten. |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Cameratype. Alleen-lezen [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Retour:**
int
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

Camera FOV (0-180 graden, gezichtsveld). Alleen-lezen float.

**Retour:**
float
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Camera-zoom (positieve waarde in procenten). Alleen-lezen float.

**Retour:**
float
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Een rotatie wordt gedefinieerd door het gebruik van een breedtegraadcoördinaat, een lengtegraadcoördinaat en een omwenteling rond de as als de breedtegraad- en lengtegraadcoördinaten. het eerste element in het geretourneerde array - breedtegraad, het tweede - lengtegraad, het derde - omwenteling. Retourneert null als geen rotatie is gedefinieerd.

**Retour:**
float[] - Array van rotatiewaarden als float[].
