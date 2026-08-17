---
title: ILightRig
second_title: Aspose.Slides for Java API Reference
description: Representa LightRig.
type: docs
url: /pt/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

Representa LightRig.
## Métodos

| Método | Descrição |
| --- | --- |
| [getDirection()](#getDirection--) | Direção da luz. |
| [setDirection(int value)](#setDirection-int-) | Direção da luz. |
| [getLightType()](#getLightType--) | Representa uma luz predefinida direita que pode ser aplicada a uma forma. |
| [setLightType(int value)](#setLightType-int-) | Representa uma luz predefinida direita que pode ser aplicada a uma forma. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Uma rotação é definida através do uso de uma coordenada de latitude, uma coordenada de longitude e uma revolução em torno do eixo como as coordenadas de latitude e longitude. |
| [getRotation()](#getRotation--) | Uma rotação é definida através do uso de uma coordenada de latitude, uma coordenada de longitude e uma revolução em torno do eixo como as coordenadas de latitude e longitude. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Direção da luz. Leitura/gravação [LightingDirection](../../com.aspose.slides/lightingdirection).

**Retorna:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Direção da luz. Leitura/gravação [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Representa uma luz predefinida direita que pode ser aplicada a uma forma. O light rig representa um grupo de luzes orientado de maneira específica em relação a uma cena 3D. Leitura/gravação [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Retorna:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

Representa uma luz predefinida direita que pode ser aplicada a uma forma. O light rig representa um grupo de luzes orientado de maneira específica em relação a uma cena 3D. Leitura/gravação [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Uma rotação é definida através do uso de uma coordenada de latitude, uma coordenada de longitude e uma revolução em torno do eixo como as coordenadas de latitude e longitude.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| latitude | float | Coordenada de latitude float |
| longitude | float | Coordenada de longitude float |
| revolution | float | Coordenada de revolução float |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Uma rotação é definida através do uso de uma coordenada de latitude, uma coordenada de longitude e uma revolução em torno do eixo como as coordenadas de latitude e longitude. primeiro elemento no array de retorno - latitude, segundo - longitude, terceiro - revolução.

**Retorna:**
float[] - Coordenadas de rotação como float[]