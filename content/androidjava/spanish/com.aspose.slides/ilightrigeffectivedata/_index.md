---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Objeto inmutable que contiene las propiedades efectivas del conjunto de luces.
type: docs
url: /es/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Objeto inmutable que contiene las propiedades efectivas del conjunto de luces.

--------------------

Esta interfaz se usa como parte de [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Métodos

| Método | Descripción |
| --- | --- |
| [getDirection()](#getDirection--) | Dirección de la luz. |
| [getLightType()](#getLightType--) | Representa una luz preestablecida que puede aplicarse a una forma. |
| [getRotation()](#getRotation--) | Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje como las coordenadas de latitud y longitud. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


Dirección de la luz. Sólo lectura [LightingDirection](../../com.aspose.slides/lightingdirection).

**Devuelve:**
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


Representa una luz preestablecida que puede aplicarse a una forma. El light rig representa un grupo de luces orientadas de una manera específica en relación con una escena 3D. Sólo lectura [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Devuelve:**
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje como las coordenadas de latitud y longitud. Primer elemento en el arreglo devuelto - latitud, segundo - longitud, tercero - revolución.

**Devuelve:**
float[] - coordenadas de rotación como float[]