---
title: Camera
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta la fotocamera.
type: docs
url: /it/com.aspose.slides/camera/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)
```
public final class Camera extends PVIObject implements ICamera
```

Rappresenta la fotocamera.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | Tipo di fotocamera. |
| [setCameraType(int value)](#setCameraType-int-) | Tipo di fotocamera. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | FOV della fotocamera (0-180 gradi, campo visivo). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | FOV della fotocamera (0-180 gradi, campo visivo). |
| [getZoom()](#getZoom--) | Zoom della fotocamera (valore positivo in percentuale). |
| [setZoom(float value)](#setZoom-float-) | Zoom della fotocamera (valore positivo in percentuale). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Una rotazione è definita mediante l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come le coordinate di latitudine e longitudine. |
| [getRotation()](#getRotation--) | Una rotazione è definita mediante l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come le coordinate di latitudine e longitudine. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versione. Solo lettura long.

**Restituisce:**
long
### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```

Tipo di fotocamera. Lettura/scrittura [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Restituisce:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```

Tipo di fotocamera. Lettura/scrittura [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```

FOV della fotocamera (0-180 gradi, campo visivo). Lettura/scrittura float.

**Restituisce:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

FOV della fotocamera (0-180 gradi, campo visivo). Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public final float getZoom()
```

Zoom della fotocamera (valore positivo in percentuale). Lettura/scrittura float.

**Restituisce:**
float
### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```

Zoom della fotocamera (valore positivo in percentuale). Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Una rotazione è definita mediante l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come le coordinate di latitudine e longitudine. Se uno qualsiasi dei valori di coordinata è Float.NaN, tutta la rotazione è indefinita.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

Una rotazione è definita mediante l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come le coordinate di latitudine e longitudine. primo elemento nell'array restituito – latitudine, secondo – longitudine, terzo – rivoluzione. Restituisce null se nessuna rotazione è definita.

**Restituisce:**
float[]