---
title: ICamera
second_title: Aspose.Slides for Java API Reference
description: Representa una cámara.
type: docs
url: /es/com.aspose.slides/icamera/
---```
public interface ICamera
```

Representa una cámara.
## Métodos

| Method | Description |
| --- | --- |
| [getCameraType()](#getCameraType--) | Tipo de cámara Lectura/escritura [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | Tipo de cámara Lectura/escritura [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | FOV de la cámara (0-180 grad, campo de visión) Lectura/escritura float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | FOV de la cámara (0-180 grad, campo de visión) Lectura/escritura float. |
| [getZoom()](#getZoom--) | Zoom de la cámara (valor positivo en porcentaje) Lectura/escritura float. |
| [setZoom(float value)](#setZoom-float-) | Zoom de la cámara (valor positivo en porcentaje) Lectura/escritura float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje como las coordenadas de latitud y longitud. |
| [getRotation()](#getRotation--) | Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje como las coordenadas de latitud y longitud. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Tipo de cámara Lectura/escritura [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Devuelve:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

Tipo de cámara Lectura/escritura [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

FOV de la cámara (0-180 grad, campo de visión) Lectura/escritura float.

**Devuelve:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

FOV de la cámara (0-180 grad, campo de visión) Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Zoom de la cámara (valor positivo en porcentaje) Lectura/escritura float.

**Devuelve:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

Zoom de la cámara (valor positivo en porcentaje) Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje como las coordenadas de latitud y longitud. Si alguno de los valores de coordenada es Float.NaN, toda la rotación queda indefinida.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| latitude | float | Valor de latitud float |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje como las coordenadas de latitud y longitud. El primer elemento del arreglo devuelto - latitud, segundo - longitud, tercero - revolución. Devuelve null si no se ha definido rotación.

**Devuelve:**
float[] - Matriz de valores de rotación como float[].