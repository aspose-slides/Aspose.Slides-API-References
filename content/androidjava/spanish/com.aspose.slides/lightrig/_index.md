---
title: LightRig
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa LightRig.
type: docs
url: /es/com.aspose.slides/lightrig/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas las interfaces implementadas:**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

Representa LightRig.
## Métodos

| Método | Descripción |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | Dirección de la luz. |
| [setDirection(int value)](#setDirection-int-) | Dirección de la luz. |
| [getLightType()](#getLightType--) | Representa una luz predefinida derecha que puede aplicarse a una forma. |
| [setLightType(int value)](#setLightType-int-) | Representa una luz predefinida derecha que puede aplicarse a una forma. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje como coordenadas de latitud y longitud. |
| [getRotation()](#getRotation--) | Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje como coordenadas de latitud y longitud. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versión. Solo lectura long.

**Devuelve:**
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```

Dirección de la luz. Lectura/escritura [LightingDirection](../../com.aspose.slides/lightingdirection).

**Devuelve:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```

Dirección de la luz. Lectura/escritura [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public final int getLightType()
```

Representa una luz predefinida derecha que puede aplicarse a una forma. El light rig representa un grupo de luces orientadas de una manera específica con respecto a una escena 3D. Lectura/escritura [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Devuelve:**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

Representa una luz predefinida derecha que puede aplicarse a una forma. El light rig representa un grupo de luces orientadas de una manera específica con respecto a una escena 3D. Lectura/escritura [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje como coordenadas de latitud y longitud. Si alguno de los valores de coordenada es Float.NaN, toda la rotación es indefinida.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje como coordenadas de latitud y longitud. Primer elemento del arreglo devuelto - latitud, segundo - longitud, tercero - revolución. Devuelve null si no se ha definido ninguna rotación.

**Devuelve:**
float[]