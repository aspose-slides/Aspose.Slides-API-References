---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective light rig properties.
type: docs
url: /cs/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Neměnný objekt, který obsahuje efektivní vlastnosti světelného rigu.

--------------------

Toto rozhraní se používá jako součást [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Metody

| Metoda | Popis |
| --- | --- |
| [getDirection()](#getDirection--) | Směr světla. |
| [getLightType()](#getLightType--) | Předdefinované pravé světlo, které lze použít na tvar. |
| [getRotation()](#getRotation--) | Rotace je definována pomocí zeměpisné souřadnice, délkové souřadnice a otáčení kolem osy jako zeměpisné a délkové souřadnice. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


Směr světla. Pouze pro čtení [LightingDirection](../../com.aspose.slides/lightingdirection).

**Vrací:**
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


Představuje předdefinované pravé světlo, které lze použít na tvar. Rig světla představuje skupinu světel orientovaných specifickým způsobem vzhledem k 3D scéně. Pouze pro čtení [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Vrací:**
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Rotace je definována pomocí zeměpisné souřadnice, délkové souřadnice a otáčení kolem osy jako zeměpisné a délkové souřadnice. První prvek v návratovém poli – zeměpisná souřadnice, druhý – délková souřadnice, třetí – otáčení.

**Vrací:**
float[] - Rotace souřadnic jako float[]