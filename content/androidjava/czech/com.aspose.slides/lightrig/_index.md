---
title: LightRig
second_title: Aspose.Slides pro Android přes referenci Java API
description: Představuje LightRig.
type: docs
url: /cs/com.aspose.slides/lightrig/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Všechny implementované rozhraní:**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

Představuje LightRig.
## Methods

| Metoda | Popis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | Směr světla. |
| [setDirection(int value)](#setDirection-int-) | Směr světla. |
| [getLightType()](#getLightType--) | Představuje přednastavené pravé světlo, které lze použít na tvar. |
| [setLightType(int value)](#setLightType-int-) | Představuje přednastavené pravé světlo, které lze použít na tvar. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Rotace je definována pomocí souřadnice zeměpisné šířky, souřadnice zeměpisné délky a otáčením kolem osy jako souřadnic zeměpisné šířky a délky. |
| [getRotation()](#getRotation--) | Rotace je definována pomocí souřadnice zeměpisné šířky, souřadnice zeměpisné délky a otáčením kolem osy jako souřadnic zeměpisné šířky a délky. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Verze. Pouze pro čtení, typ long.

**Vrací:**
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```


Směr světla. Čtení/zápis [LightingDirection](../../com.aspose.slides/lightingdirection).

**Vrací:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


Směr světla. Čtení/zápis [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public final int getLightType()
```


Představuje přednastavené pravé světlo, které lze použít na tvar. Light rig představuje skupinu světel orientovaných specifickým způsobem vzhledem k 3D scéně. Čtení/zápis [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Vrací:**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```


Představuje přednastavené pravé světlo, které lze použít na tvar. Light rig představuje skupinu světel orientovaných specifickým způsobem vzhledem k 3D scéně. Čtení/zápis [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```


Rotace je definována pomocí souřadnice zeměpisné šířky, souřadnice zeměpisné délky a otáčením kolem osy jako souřadnic zeměpisné šířky a délky. Pokud je některá hodnota souřadnice Float.NaN, je celá rotace nedefinovaná.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public final float[] getRotation()
```


Rotace je definována pomocí souřadnice zeměpisné šířky, souřadnice zeměpisné délky a otáčením kolem osy jako souřadnic zeměpisné šířky a délky. první prvek v návratovém poli - zeměpisná šířka, druhý - zeměpisná délka, třetí - otáčení. Vrací null, pokud není definována žádná rotace.

**Vrací:**
float[]