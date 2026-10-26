---
title: ILightRig
second_title: Aspose.Slides for Java API Reference
description: Rappresenta LightRig.
type: docs
url: /it/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

Rappresenta LightRig.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDirection()](#getDirection--) | Direzione della luce. |
| [setDirection(int value)](#setDirection-int-) | Direzione della luce. |
| [getLightType()](#getLightType--) | Rappresenta una luce preimpostata a destra che può essere applicata a una forma. |
| [setLightType(int value)](#setLightType-int-) | Rappresenta una luce preimpostata a destra che può essere applicata a una forma. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Una rotazione è definita mediante l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come le coordinate di latitudine e longitudine. |
| [getRotation()](#getRotation--) | Una rotazione è definita mediante l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come le coordinate di latitudine e longitudine. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Direzione della luce. Lettura/Scrittura [LightingDirection](../../com.aspose.slides/lightingdirection).

**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Direzione della luce. Lettura/Scrittura [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Rappresenta una luce preimpostata a destra che può essere applicata a una forma. Il light rig rappresenta un gruppo di luci orientate in un modo specifico rispetto a una scena 3D. Lettura/Scrittura [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Returns:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

Rappresenta una luce preimpostata a destra che può essere applicata a una forma. Il light rig rappresenta un gruppo di luci orientate in un modo specifico rispetto a una scena 3D. Lettura/Scrittura [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Una rotazione è definita mediante l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come le coordinate di latitudine e longitudine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| latitude | float | Coordinata di latitudine float |
| longitude | float | Coordinata di longitudine float |
| revolution | float | Coordinata di rivoluzione float |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Una rotazione è definita mediante l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come le coordinate di latitudine e longitudine. primo elemento nell'array restituito - latitudine, secondo - longitudine, terzo - rivoluzione.

**Returns:**
float[] - Coordinate di rotazione come float[]