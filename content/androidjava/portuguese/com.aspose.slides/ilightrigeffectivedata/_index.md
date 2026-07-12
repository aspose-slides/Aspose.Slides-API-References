---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
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
| [getDirection()](#getDirection--) | Light direction. |
| [getLightType()](#getLightType--) | Represents a preset light right that can be applied to a shape. |
| [getRotation()](#getRotation--) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |
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

Representa uma luz pré-definida que pode ser aplicada a uma forma. O rig de luz representa um grupo de luzes orientadas de uma maneira específica em relação a uma cena 3D. Somente leitura [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Retorna:**
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Uma rotação é definida através do uso de uma coordenada de latitude, uma coordenada de longitude e uma revolução em torno do eixo como as coordenadas de latitude e longitude. Primeiro elemento no array retornado - latitude, segundo - longitude, terceiro - revolução.

**Retorna:**
float[] - Coordenadas de rotação como float[]