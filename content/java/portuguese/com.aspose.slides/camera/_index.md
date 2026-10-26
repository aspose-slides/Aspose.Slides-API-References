---
title: Camera
second_title: Referência da API Aspose.Slides para Java
description: Representa Camera.
type: docs
url: /pt/com.aspose.slides/camera/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)
```
public final class Camera extends PVIObject implements ICamera
```

Representa Camera.
## Métodos

| Método | Descrição |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | Tipo de Camera. |
| [setCameraType(int value)](#setCameraType-int-) | Tipo de Camera. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | FOV da Camera (0-180 graus, campo de Visão). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | FOV da Camera (0-180 graus, campo de Visão). |
| [getZoom()](#getZoom--) | Zoom da Camera (valor positivo em porcentagem). |
| [setZoom(float value)](#setZoom-float-) | Zoom da Camera (valor positivo em porcentagem). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Uma rotação é definida pelo uso de uma coordenada de latitude, uma coordenada de longitude e uma revolução em torno do eixo como as coordenadas de latitude e longitude. |
| [getRotation()](#getRotation--) | Uma rotação é definida pelo uso de uma coordenada de latitude, uma coordenada de longitude e uma revolução em torno do eixo como as coordenadas de latitude e longitude. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versão. Somente leitura long.

**Retorna:**
long
### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```


Tipo de Camera. Leitura/gravação [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Retorna:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```


Tipo de Camera. Leitura/gravação [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```


FOV da Camera (0-180 graus, campo de Visão). Leitura/gravação float.

**Retorna:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```


FOV da Camera (0-180 graus, campo de Visão). Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public final float getZoom()
```


Zoom da Camera (valor positivo em porcentagem). Leitura/gravação float.

**Retorna:**
float
### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```


Zoom da Camera (valor positivo em porcentagem). Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```


Uma rotação é definida pelo uso de uma coordenada de latitude, uma coordenada de longitude e uma revolução em torno do eixo como as coordenadas de latitude e longitude. Se algum valor de coordenada for Float.NaN, toda a rotação fica indefinida.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public final float[] getRotation()
```


Uma rotação é definida pelo uso de uma coordenada de latitude, uma coordenada de longitude e uma revolução em torno do eixo como as coordenadas de latitude e longitude. Primeiro elemento no array retornado - latitude, segundo - longitude, terceiro - revolução. Retorna null se nenhuma rotação estiver definida.

**Retorna:**
float[]