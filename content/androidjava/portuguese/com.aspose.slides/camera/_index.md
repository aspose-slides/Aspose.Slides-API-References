---
title: Camera
second_title: Aspose.Slides para Android via Referência da API Java
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

| Method | Descrição |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | Tipo da Camera. |
| [setCameraType(int value)](#setCameraType-int-) | Tipo da Camera. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180 graus, campo de visão). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Camera FOV (0-180 graus, campo de visão). |
| [getZoom()](#getZoom--) | Camera zoom (valor positivo em porcentagem). |
| [setZoom(float value)](#setZoom-float-) | Camera zoom (valor positivo em porcentagem). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Uma rotação é definida através do uso de uma coordenada de latitude, uma coordenada de longitude e uma revolução em torno do eixo como as coordenadas de latitude e longitude. |
| [getRotation()](#getRotation--) | Uma rotação é definida através do uso de uma coordenada de latitude, uma coordenada de longitude e uma revolução em torno do eixo como as coordenadas de latitude e longitude. |
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


Tipo da Camera. Leitura/gravação [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Retorna:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```


Tipo da Camera. Leitura/gravação [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```


Camera FOV (0-180 graus, campo de visão). Leitura/gravação float.

**Retorna:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```


Camera FOV (0-180 graus, campo de visão). Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public final float getZoom()
```


Camera zoom (valor positivo em porcentagem). Leitura/gravação float.

**Retorna:**
float
### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```


Camera zoom (valor positivo em porcentagem). Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```


Uma rotação é definida através do uso de uma coordenada de latitude, uma coordenada de longitude e uma revolução em torno do eixo como as coordenadas de latitude e longitude. Se algum valor de coordenada for Float.NaN, toda a rotação fica indefinida.

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


Uma rotação é definida através do uso de uma coordenada de latitude, uma coordenada de longitude e uma revolução em torno do eixo como as coordenadas de latitude e longitude. primeiro elemento no array retornado - latitude, segundo - longitude, terceiro - revolução. Retorna null se nenhuma rotação estiver definida.

**Retorna:**
float[]