---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective light rig properties.
type: docs
url: /it/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Oggetto immutabile che contiene le proprietà effective del rig di luce.

--------------------

Questa interfaccia è usata come parte di [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDirection()](#getDirection--) | Direzione della luce. |
| [getLightType()](#getLightType--) | Rappresenta una luce predefinita a destra che può essere applicata a una forma. |
| [getRotation()](#getRotation--) | Una rotazione è definita mediante l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come coordinate di latitudine e longitudine. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


Direzione della luce. Di sola lettura [LightingDirection](../../com.aspose.slides/lightingdirection).

**Returns:**
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


Rappresenta una luce predefinita a destra che può essere applicata a una forma. Il rig di luce rappresenta un gruppo di luci orientate in modo specifico rispetto a una scena 3D. Di sola lettura [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Returns:**
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Una rotazione è definita mediante l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come coordinate di latitudine e longitudine. Il primo elemento nell'array restituito - latitudine, il secondo - longitudine, il terzo - rivoluzione.

**Returns:**
float[] - Coordinate di rotazione come float[]