---
title: ICameraEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Objeto inmutable que contiene propiedades de cámara efectivas.
type: docs
url: /es/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

Objeto inmutable que contiene propiedades de cámara efectivas.

--------------------

Esta interfaz se utiliza como parte de [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Métodos

| Método | Descripción |
| --- | --- |
| [getCameraType()](#getCameraType--) | Tipo de cámara. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | FOV de la cámara (0-180°, campo de visión). |
| [getZoom()](#getZoom--) | Zoom de la cámara (valor positivo en porcentaje). |
| [getRotation()](#getRotation--) | Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje como las coordenadas de latitud y longitud. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


Tipo de cámara. Solo lectura [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Returns:**
int
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


FOV de la cámara (0-180°, campo de visión). Solo lectura float.

**Returns:**
float
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


Zoom de la cámara (valor positivo en porcentaje). Solo lectura float.

**Returns:**
float
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje como las coordenadas de latitud y longitud. Primer elemento en el array devuelto - latitud, segundo - longitud, tercero - revolución. Devuelve null si no se ha definido ninguna rotación.

**Returns:**
float[] - Matriz de valores de rotación como float[].