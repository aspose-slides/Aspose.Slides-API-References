---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective light rig properties.
type: docs
url: /es/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Objeto inmutable que contiene propiedades efectivas del rig de luz.

--------------------

Esta interfaz se usa como parte de [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Métodos

| Método | Descripción |
| --- | --- |
| [getDirection()](#getDirection--) | Dirección de luz. |
| [getLightType()](#getLightType--) | Representa una luz predefinida que puede aplicarse a una forma. |
| [getRotation()](#getRotation--) | Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje como coordenadas de latitud y longitud. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


Dirección de luz. Solo lectura [LightingDirection](../../com.aspose.slides/lightingdirection).

**Devuelve:**
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


Representa una luz predefinida que puede aplicarse a una forma. El rig de luz representa un grupo de luces orientadas de una manera específica respecto a una escena 3D. Solo lectura [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Devuelve:**
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje como coordenadas de latitud y longitud. Primer elemento en la matriz devuelta: latitud; segundo: longitud; tercero: revolución.

**Devuelve:**
float[] - Coordenadas de rotación como float[]