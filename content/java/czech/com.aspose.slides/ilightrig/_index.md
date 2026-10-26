---
title: ILightRig
second_title: Aspose.Slides for Java API Reference
description: Represents LightRig.
type: docs
url: /cs/com.aspose.slides/ilightrig/
---
```
public interface ILightRig
```

Representuje LightRig.
## Metody

| Metoda | Popis |
| --- | --- |
| [getDirection()](#getDirection--) | Směr světla. |
| [setDirection(int value)](#setDirection-int-) | Směr světla. |
| [getLightType()](#getLightType--) | Representuje přednastavené pravé světlo, které lze použít na tvar. |
| [setLightType(int value)](#setLightType-int-) | Representuje přednastavené pravé světlo, které lze použít na tvar. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Rotace je definována pomocí souřadnice zeměpisné šířky, souřadnice zeměpisné délky a otáčení kolem osy jako souřadnice zeměpisné šířky a délky. |
| [getRotation()](#getRotation--) | Rotace je definována pomocí souřadnice zeměpisné šířky, souřadnice zeměpisné délky a otáčení kolem osy jako souřadnice zeměpisné šířky a délky. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Směr světla. Čtení/zápis [LightingDirection](../../com.aspose.slides/lightingdirection).

**Vrací:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Směr světla. Čtení/zápis [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Representuje přednastavené pravé světlo, které lze použít na tvar. Light rig představuje skupinu světel orientovaných určitým způsobem vzhledem k 3D scéně. Čtení/zápis [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Vrací:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

Representuje přednastavené pravé světlo, které lze použít na tvar. Light rig představuje skupinu světel orientovaných určitým způsobem vzhledem k 3D scéně. Čtení/zápis [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Rotace je definována pomocí souřadnice zeměpisné šířky, souřadnice zeměpisné délky a otáčení kolem osy jako souřadnice zeměpisné šířky a délky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| latitude | float | Souřadnice zeměpisné šířky float |
| longitude | float | Souřadnice zeměpisné délky float |
| revolution | float | Souřadnice otáčení float |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Rotace je definována pomocí souřadnice zeměpisné šířky, souřadnice zeměpisné délky a otáčení kolem osy jako souřadnice zeměpisné šířky a délky. první prvek v návratovém poli – zeměpisná šířka, druhý – zeměpisná délka, třetí – otáčení.

**Vrací:**
float[] – souřadnice rotace jako float[]