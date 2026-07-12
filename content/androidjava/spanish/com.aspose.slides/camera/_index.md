---
title: Camera
second_title: Referencia de API Java de Aspose.Slides para Android
description: Representa una cámara.
type: docs
url: /es/com.aspose.slides/camera/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas las interfaces implementadas:**
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)
```
public final class Camera extends PVIObject implements ICamera
```

Representa una cámara.
## Métodos

| Método | Descripción |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | Tipo de cámara. |
| [setCameraType(int value)](#setCameraType-int-) | Tipo de cámara. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | FOV de la cámara (0-180 deg, campo de visión). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | FOV de la cámara (0-180 deg, campo de visión). |
| [getZoom()](#getZoom--) | Zoom de la cámara (valor positivo en porcentaje). |
| [setZoom(float value)](#setZoom-float-) | Zoom de la cámara (valor positivo en porcentaje). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje como coordenadas de latitud y longitud. |
| [getRotation()](#getRotation--) | Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje como coordenadas de latitud y longitud. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versión. Solo lectura long.

**Devuelve:**
long
### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```

Tipo de cámara. Lectura/escritura [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Devuelve:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```

Tipo de cámara. Lectura/escritura [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```

FOV de la cámara (0-180 deg, campo de visión). Lectura/escritura float.

**Devuelve:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

FOV de la cámara (0-180 deg, campo de visión). Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public final float getZoom()
```

Zoom de la cámara (valor positivo en porcentaje). Lectura/escritura float.

**Devuelve:**
float
### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```

Zoom de la cámara (valor positivo en porcentaje). Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje como coordenadas de latitud y longitud. Si algún valor de coordenada es Float.NaN, toda la rotación está indefinida.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje como coordenadas de latitud y longitud. primer elemento en el arreglo devuelto - latitud, segundo - longitud, tercero - revolución. Devuelve null si no hay rotación definida.

**Devuelve:**
float[]