---
title: ILightRig
second_title: Aspose.Slides for Android via Java API Reference
description: Representa LightRig.
type: docs
url: /es/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

Representa LightRig.
## Métodos

| Método | Descripción |
| --- | --- |
| [getDirection()](#getDirection--) | Dirección de luz. |
| [setDirection(int value)](#setDirection-int-) | Dirección de luz. |
| [getLightType()](#getLightType--) | Representa una luz preestablecida derecha que puede aplicarse a una forma. |
| [setLightType(int value)](#setLightType-int-) | Representa una luz preestablecida derecha que puede aplicarse a una forma. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje según las coordenadas de latitud y longitud. |
| [getRotation()](#getRotation--) | Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje según las coordenadas de latitud y longitud. |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Dirección de luz. Lectura/escritura [LightingDirection](../../com.aspose.slides/lightingdirection).

**Devuelve:**
int

### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Dirección de luz. Lectura/escritura [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Representa una luz preestablecida derecha que puede aplicarse a una forma. El light rig representa un grupo de luces orientadas de una forma específica respecto a una escena 3D. Lectura/escritura [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Devuelve:**
int

### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

Representa una luz preestablecida derecha que puede aplicarse a una forma. El light rig representa un grupo de luces orientadas de una forma específica respecto a una escena 3D. Lectura/escritura [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje según las coordenadas de latitud y longitud.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| latitude | float | Coordenada de latitud float |
| longitude | float | Coordenada de longitud float |
| revolution | float | Coordenada de revolución float |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje según las coordenadas de latitud y longitud. primer elemento en el array devuelto - latitud, segundo - longitud, tercero - revolución.

**Devuelve:**
float[] - Coordenadas de rotación como float[]