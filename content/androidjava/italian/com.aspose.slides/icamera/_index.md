---
title: ICamera
second_title: Aspose.Slides per Android tramite Riferimento API Java
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
| [getCameraType()](#getCameraType--) | Tipo fotocamera Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | Tipo fotocamera Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | FOV fotocamera (0-180 deg, campo di visuale) Read/write float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | FOV fotocamera (0-180 deg, campo di visuale) Read/write float. |
| [getZoom()](#getZoom--) | Zoom fotocamera (valore positivo in percentuale) Read/write float. |
| [setZoom(float value)](#setZoom-float-) | Zoom fotocamera (valore positivo in percentuale) Read/write float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Una rotazione è definita mediante l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come le coordinate di latitudine e longitudine. |
| [getRotation()](#getRotation--) | Una rotazione è definita mediante l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come le coordinate di latitudine e longitudine. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


Tipo fotocamera Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Restituisce:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```


Tipo fotocamera Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


FOV fotocamera (0-180 deg, campo di visuale) Read/write float.

**Restituisce:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```


FOV fotocamera (0-180 deg, campo di visuale) Read/write float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


Zoom fotocamera (valore positivo in percentuale) Read/write float.

**Restituisce:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```


Zoom fotocamera (valore positivo in percentuale) Read/write float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```


Una rotazione è definita mediante l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come le coordinate di latitudine e longitudine. Se uno qualsiasi dei valori di coordinata è Float.NaN, l'intera rotazione è indefinita.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| latitude | float | Valore di latitudine float |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Una rotazione è definita mediante l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come le coordinate di latitudine e longitudine. primo elemento nell'array restituito - latitudine, secondo - longitudine, terzo - rivoluzione. Restituisce null se nessuna rotazione è definita.

**Restituisce:**
float[] - Array di valori di rotazione come float[].