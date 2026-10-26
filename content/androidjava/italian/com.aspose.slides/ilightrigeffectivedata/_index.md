---
title: ILightRigEffectiveData
second_title: Aspose.Slides per Android tramite Java API Reference
description: Oggetto immutabile che contiene le proprietà effettive del rig di luce.
type: docs
url: /it/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Oggetto immutabile che contiene le proprietà effettive del rig di luce.

--------------------

Questa interfaccia è usata come parte di [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDirection()](#getDirection--) | Direzione della luce. |
| [getLightType()](#getLightType--) | Rappresenta una luce preimpostata che può essere applicata a una forma. |
| [getRotation()](#getRotation--) | Una rotazione è definita attraverso l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come le coordinate di latitudine e longitudine. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


Direzione della luce. Solo lettura [LightingDirection](../../com.aspose.slides/lightingdirection).

**Restituisce:**
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


Rappresenta una luce preimpostata che può essere applicata a una forma. Il rig di luce rappresenta un gruppo di luci orientate in modo specifico rispetto a una scena 3D. Solo lettura [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Restituisce:**
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Una rotazione è definita attraverso l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come le coordinate di latitudine e longitudine. Il primo elemento nell'array restituito - latitudine, il secondo - longitudine, il terzo - rivoluzione.

**Restituisce:**
float[] - Coordinate di rotazione come float[]