---
title: ICamera
second_title: Aspose.Slides for Android via Java API Reference
description: Represents Camera.
type: docs
url: /pt/com.aspose.slides/icamera/
---```
public interface ICamera
```

Representa Câmera.
## Métodos

| Método | Descrição |
| --- | --- |
| [getCameraType()](#getCameraType--) | Tipo de câmera Leitura/gravação [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | Tipo de câmera Leitura/gravação [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | FOV da câmera (0-180 deg, field of View) Leitura/gravação float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | FOV da câmera (0-180 deg, field of View) Leitura/gravação float. |
| [getZoom()](#getZoom--) | Zoom da câmera (valor positivo em porcentagem) Leitura/gravação float. |
| [setZoom(float value)](#setZoom-float-) | Zoom da câmera (valor positivo em porcentagem) Leitura/gravação float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Uma rotação é definida usando uma coordenada de latitude, uma coordenada de longitude e uma revolução ao redor do eixo como as coordenadas de latitude e longitude. |
| [getRotation()](#getRotation--) | Uma rotação é definida usando uma coordenada de latitude, uma coordenada de longitude e uma revolução ao redor do eixo como as coordenadas de latitude e longitude. |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Tipo de câmera Leitura/gravação [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Retorna:**
int

### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

Tipo de câmera Leitura/gravação [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

FOV da câmera (0-180 deg, field of View) Leitura/gravação float.

**Retorna:**
float

### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

FOV da câmera (0-180 deg, field of View) Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Zoom da câmera (valor positivo em porcentagem) Leitura/gravação float.

**Retorna:**
float

### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

Zoom da câmera (valor positivo em porcentagem) Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Uma rotação é definida usando uma coordenada de latitude, uma coordenada de longitude e uma revolução ao redor do eixo como as coordenadas de latitude e longitude. Se algum valor da coordenada for Float.NaN, toda a rotação fica indefinida.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| latitude | float | Valor de latitude float |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Uma rotação é definida usando uma coordenada de latitude, uma coordenada de longitude e uma revolução ao redor do eixo como as coordenadas de latitude e longitude. primeiro elemento no array retornado - latitude, segundo - longitude, terceiro - revolução. Retorna null se nenhuma rotação estiver definida.

**Retorna:**
float[] - Array de valores de rotação como float[].