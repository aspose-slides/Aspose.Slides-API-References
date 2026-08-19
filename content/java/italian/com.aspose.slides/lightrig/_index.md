---
title: LightRig
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta LightRig.
type: docs
url: /it/com.aspose.slides/lightrig/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tutte le interfacce implementate:**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

Rappresenta LightRig.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | Direzione della luce. |
| [setDirection(int value)](#setDirection-int-) | Direzione della luce. |
| [getLightType()](#getLightType--) | Rappresenta una luce predefinita a destra che può essere applicata a una forma. |
| [setLightType(int value)](#setLightType-int-) | Rappresenta una luce predefinita a destra che può essere applicata a una forma. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Una rotazione è definita mediante l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come le coordinate di latitudine e longitudine. |
| [getRotation()](#getRotation--) | Una rotazione è definita mediante l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come le coordinate di latitudine e longitudine. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versione. Solo lettura long.

**Restituisce:**
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```

Direzione della luce. Lettura/scrittura [LightingDirection](../../com.aspose.slides/lightingdirection).

**Restituisce:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```

Direzione della luce. Lettura/scrittura [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public final int getLightType()
```

Rappresenta una luce predefinita a destra che può essere applicata a una forma. Il light rig rappresenta un gruppo di luci orientate in un modo specifico rispetto a una scena 3D. Lettura/scrittura [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Restituisce:**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

Rappresenta una luce predefinita a destra che può essere applicata a una forma. Il light rig rappresenta un gruppo di luci orientate in un modo specifico rispetto a una scena 3D. Lettura/scrittura [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Una rotazione è definita mediante l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come le coordinate di latitudine e longitudine. Se uno qualsiasi dei valori delle coordinate è Float.NaN, tutta la rotazione è indefinita.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

Una rotazione è definita mediante l'uso di una coordinata di latitudine, una coordinata di longitudine e una rivoluzione attorno all'asse come le coordinate di latitudine e longitudine. primo elemento nell'array restituito – latitude, secondo – longitude, terzo – revolution. Restituisce null se nessuna rotazione definita.

**Restituisce:**
float[]