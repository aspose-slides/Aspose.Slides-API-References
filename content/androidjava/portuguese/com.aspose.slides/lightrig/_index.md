---
title: LightRig
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa LightRig.
type: docs
url: /pt/com.aspose.slides/lightrig/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

Representa LightRig.
## Métodos

| Método | Descrição |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | Direção da luz. |
| [setDirection(int value)](#setDirection-int-) | Direção da luz. |
| [getLightType()](#getLightType--) | Representa uma luz predefinida à direita que pode ser aplicada a uma forma. |
| [setLightType(int value)](#setLightType-int-) | Representa uma luz predefinida à direita que pode ser aplicada a uma forma. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Uma rotação é definida através do uso de uma coordenada de latitude, uma coordenada de longitude e uma revolução ao redor do eixo como as coordenadas de latitude e longitude. |
| [getRotation()](#getRotation--) | Uma rotação é definida através do uso de uma coordenada de latitude, uma coordenada de longitude e uma revolução ao redor do eixo como as coordenadas de latitude e longitude. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versão. Somente leitura long.

**Retorna:**
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```

Direção da luz. Leitura/gravação [LightingDirection](../../com.aspose.slides/lightingdirection).

**Retorna:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```

Direção da luz. Leitura/gravação [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public final int getLightType()
```

Representa uma luz predefinida à direita que pode ser aplicada a uma forma. O light rig representa um grupo de luzes orientadas de maneira específica em relação a uma cena 3D. Leitura/gravação [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Retorna:**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

Representa uma luz predefinida à direita que pode ser aplicada a uma forma. O light rig representa um grupo de luzes orientadas de maneira específica em relação a uma cena 3D. Leitura/gravação [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Uma rotação é definida através do uso de uma coordenada de latitude, uma coordenada de longitude e uma revolução ao redor do eixo como as coordenadas de latitude e longitude. Se algum valor de coordenada for Float.NaN, toda a rotação fica indefinida.

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

Uma rotação é definida através do uso de uma coordenada de latitude, uma coordenada de longitude e uma revolução ao redor do eixo como as coordenadas de latitude e longitude. Primeiro elemento no array retornado - latitude, segundo - longitude, terceiro - revolução. Retorna null se nenhuma rotação for definida.

**Retorna:**
float[]