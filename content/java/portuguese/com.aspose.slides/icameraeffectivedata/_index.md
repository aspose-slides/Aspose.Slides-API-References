---
title: ICameraEffectiveData
second_title: Aspose.Slides for Java API Reference
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

| Método | Descrição |
| --- | --- |
| [getCameraType()](#getCameraType--) | Tipo da câmera. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | FOV da câmera (0-180 deg, campo de Visão). |
| [getZoom()](#getZoom--) | Zoom da câmera (valor positivo em porcentagem). |
| [getRotation()](#getRotation--) | Uma rotação é definida pelo uso de uma coordenada de latitude, uma coordenada de longitude e uma revolução em torno do eixo conforme as coordenadas de latitude e longitude. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


Tipo da câmera. Somente leitura [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Retorna:**
int
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


FOV da câmera (0-180 deg, campo de Visão). Somente leitura float.

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


Uma rotação é definida pelo uso de uma coordenada de latitude, uma coordenada de longitude e uma revolução em torno do eixo conforme as coordenadas de latitude e longitude. Primeiro elemento no array retornado - latitude, segundo - longitude, terceiro - revolução. Retorna nulo se nenhuma rotação estiver definida.

**Retorna:**
float[] - Array de valores de rotação como float[].