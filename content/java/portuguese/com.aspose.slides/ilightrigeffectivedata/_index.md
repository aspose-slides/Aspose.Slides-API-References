---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Objeto imutável que contém propriedades efetivas do rig de luz.
type: docs
url: /pt/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Objeto imutável que contém propriedades efetivas do rig de luz.

--------------------

Esta interface é usada como parte de [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Métodos

| Método | Descrição |
| --- | --- |
| [getDirection()](#getDirection--) | Direção da luz. |
| [getLightType()](#getLightType--) | Representa uma luz predefinida que pode ser aplicada a uma forma. |
| [getRotation()](#getRotation--) | Uma rotação é definida através do uso de uma coordenada de latitude, uma coordenada de longitude e uma revolução ao redor do eixo, usando as coordenadas de latitude e longitude. |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Direção da luz. Somente leitura [LightingDirection](../../com.aspose.slides/lightingdirection).

**Retorna:**
int

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Representa uma luz predefinida que pode ser aplicada a uma forma. O rig de luz representa um grupo de luzes orientadas de forma específica em relação a uma cena 3D. Somente leitura [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Retorna:**
int

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Uma rotação é definida através do uso de uma coordenada de latitude, uma coordenada de longitude e uma revolução ao redor do eixo, usando as coordenadas de latitude e longitude. Primeiro elemento no array retornado - latitude, segundo - longitude, terceiro - revolução.

**Retorna:**
float[] - coordenadas de rotação como float[]