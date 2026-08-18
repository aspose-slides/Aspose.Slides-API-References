---
title: ICameraEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective camera properties.
type: docs
url: /es/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

Objeto inmutable que contiene propiedades de cámara efectivas.

--------------------

Esta interfaz se usa como parte de [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Métodos

| Method | Description |
| --- | --- |
| [getCameraType()](#getCameraType--) | Tipo de cámara. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | FOV de la cámara (0-180 deg, campo de visión). |
| [getZoom()](#getZoom--) | Zoom de la cámara (valor positivo en porcentaje). |
| [getRotation()](#getRotation--) | Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje como las coordenadas de latitud y longitud. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


Tipo de cámara. Solo lectura [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Devuelve:**
int
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


FOV de la cámara (0-180 deg, campo de visión). Solo lectura float.

**Devuelve:**
float
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


Zoom de la cámara (valor positivo en porcentaje). Solo lectura float.

**Devuelve:**
float
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje como las coordenadas de latitud y longitud. primer elemento en el array de retorno - latitud, segundo - longitud, tercero - revolución. Devuelve null si no se ha definido una rotación.

**Devuelve:**
float[] - Array de valores de rotación como float[].