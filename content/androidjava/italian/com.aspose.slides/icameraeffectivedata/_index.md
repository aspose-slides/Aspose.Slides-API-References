---
title: ICameraEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective camera properties.
type: docs
url: /it/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

Oggetto immutabile che contiene le proprietà effective della fotocamera.

--------------------

Questa interfaccia è usata come parte di [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCameraType()](#getCameraType--) | Tipo di fotocamera. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | FOV della fotocamera (0-180 gradi, campo visivo). |
| [getZoom()](#getZoom--) | Zoom della fotocamera (valore positivo in percentuale). |
| [getRotation()](#getRotation--) | Una rotazione è definita mediante l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come le coordinate di latitudine e longitudine. |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Tipo di fotocamera. Sola lettura [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Restituisce:**
int

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

FOV della fotocamera (0-180 gradi, campo visivo). Sola lettura float.

**Restituisce:**
float

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Zoom della fotocamera (valore positivo in percentuale). Sola lettura float.

**Restituisce:**
float

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Una rotazione è definita mediante l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come le coordinate di latitudine e longitudine. primo elemento nell'array restituito - latitudine, secondo - longitudine, terzo - rivoluzione. Restituisce null se non è definita alcuna rotazione.

**Restituisce:**
float[] - Array di valori di rotazione come float[].