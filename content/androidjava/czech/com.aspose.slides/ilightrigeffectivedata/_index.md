---
title: ILightRigEffectiveData
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Neměnný objekt, který obsahuje efektivní vlastnosti osvětlení.
type: docs
url: /cs/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Neměnný objekt, který obsahuje efektivní vlastnosti osvětlení.

--------------------

Toto rozhraní se používá jako součást [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Metody

| Method | Description |
| --- | --- |
| [getDirection()](#getDirection--) | Směr světla. |
| [getLightType()](#getLightType--) | Představuje přednastavené pravé světlo, které lze použít na tvar. |
| [getRotation()](#getRotation--) | Rotace je definována pomocí souřadnice zeměpisné šířky, souřadnice zeměpisné délky a otáčením kolem osy jako souřadnice zeměpisné šířky a délky. |
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

Představuje přednastavené pravé světlo, které lze použít na tvar. Sada světel představuje skupinu světel orientovaných specifickým způsobem vzhledem k 3D scéně. Pouze pro čtení [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Vrací:**
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Rotace je definována pomocí souřadnice zeměpisné šířky, souřadnice zeměpisné délky a otáčením kolem osy jako souřadnice zeměpisné šířky a délky. První prvek v návratovém poli – šířka, druhý – délka, třetí – revoluce.

**Vrací:**
float[] – souřadnice rotace jako float[]