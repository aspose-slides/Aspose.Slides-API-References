---
title: ICamera
second_title: Aspose.Slides for Java API Reference
description: Rappresenta la fotocamera.
type: docs
url: /it/com.aspose.slides/icamera/
---```
public interface ICamera
```

Rappresenta la fotocamera.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCameraType()](#getCameraType--) | Tipo fotocamera Lettura/Scrittura [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | Tipo fotocamera Lettura/Scrittura [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | FOV della fotocamera (0-180 gradi, campo visivo) Lettura/Scrittura float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | FOV della fotocamera (0-180 gradi, campo visivo) Lettura/Scrittura float. |
| [getZoom()](#getZoom--) | Zoom della fotocamera (valore positivo in percentuale) Lettura/Scrittura float. |
| [setZoom(float value)](#setZoom-float-) | Zoom della fotocamera (valore positivo in percentuale) Lettura/Scrittura float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Una rotazione è definita mediante l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come le coordinate di latitudine e longitudine. |
| [getRotation()](#getRotation--) | Una rotazione è definita mediante l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come le coordinate di latitudine e longitudine. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Tipo fotocamera Lettura/Scrittura [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Restituisce:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

Tipo fotocamera Lettura/Scrittura [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

FOV della fotocamera (0-180 gradi, campo visivo) Lettura/Scrittura float.

**Restituisce:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

FOV della fotocamera (0-180 gradi, campo visivo) Lettura/Scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Zoom della fotocamera (valore positivo in percentuale) Lettura/Scrittura float.

**Restituisce:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

Zoom della fotocamera (valore positivo in percentuale) Lettura/Scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Una rotazione è definita mediante l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come le coordinate di latitudine e longitudine. Se uno qualsiasi dei valori delle coordinate è Float.NaN, tutta la rotazione è indefinita.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| latitude | float | valore di latitudine float |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Una rotazione è definita mediante l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come le coordinate di latitudine e longitudine. primo elemento nell'array restituito - latitudine, secondo - longitudine, terzo - rivoluzione. Restituisce null se nessuna rotazione è definita.

**Restituisce:**
float[] - Array di valori di rotazione come float[].