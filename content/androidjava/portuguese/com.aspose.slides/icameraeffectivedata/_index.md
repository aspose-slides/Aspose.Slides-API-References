---
title: ICameraEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Objeto imutável que contém propriedades efetivas da câmera.
type: docs
url: /pt/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

Objeto imutável que contém propriedades efetivas da câmera.

--------------------

Esta interface é usada como parte de [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Métodos

| Method | Description |
| --- | --- |
| [getCameraType()](#getCameraType--) | Tipo de câmera. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | FOV da câmera (0-180 graus, campo de visão). |
| [getZoom()](#getZoom--) | Zoom da câmera (valor positivo em porcentagem). |
| [getRotation()](#getRotation--) | Uma rotação é definida através do uso de uma coordenada de latitude, uma coordenada de longitude e uma revolução em torno do eixo como as coordenadas de latitude e longitude. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Tipo de câmera. Somente leitura [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Retorna:**
int
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

FOV da câmera (0-180 graus, campo de visão). Somente leitura float.

**Retorna:**
float
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Zoom da câmera (valor positivo em porcentagem). Somente leitura float.

**Retorna:**
float
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Uma rotação é definida através do uso de uma coordenada de latitude, uma coordenada de longitude e uma revolução em torno do eixo como as coordenadas de latitude e longitude. primeiro elemento no array de retorno - latitude, segundo - longitude, terceiro - revolução. Retorna nulo se nenhuma rotação estiver definida.

**Retorna:**
float[] - Array de valores de rotação como float[].