---
title: LightRig
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje LightRig.
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

Reprezentuje LightRig.
## Metody

| Metoda | Popis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | Směr světla. |
| [setDirection(int value)](#setDirection-int-) | Směr světla. |
| [getLightType()](#getLightType--) | Reprezentuje předdefinované světlo vpravo, které lze použít na tvar. |
| [setLightType(int value)](#setLightType-int-) | Reprezentuje předdefinované světlo vpravo, které lze použít na tvar. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Rotace je definována pomocí souřadnice latitude, souřadnice longitude a otáčení kolem osy podle souřadnic latitude a longitude. |
| [getRotation()](#getRotation--) | Rotace je definována pomocí souřadnice latitude, souřadnice longitude a otáčení kolem osy podle souřadnic latitude a longitude. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze pro čtení long.

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

Reprezentuje předdefinované světlo vpravo, které lze použít na tvar. Light rig představuje skupinu světel orientovaných určitým způsobem vzhledem k 3D scéně. Čtení/zápis [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Vrací:**
int

### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

Reprezentuje předdefinované světlo vpravo, které lze použít na tvar. Light rig představuje skupinu světel orientovaných určitým způsobem vzhledem k 3D scéně. Čtení/zápis [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Rotace je definována pomocí souřadnice latitude, souřadnice longitude a otáčení kolem osy podle souřadnic latitude a longitude. Pokud je hodnota kteréhokoli souřadnicového parametru Float.NaN, je celá rotace nedefinována.

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

Rotace je definována pomocí souřadnice latitude, souřadnice longitude a otáčení kolem osy podle souřadnic latitude a longitude. první prvek v návratovém poli – latitude, druhý – longitude, třetí – revolution. Vrací null, pokud není žádná rotace definována.

**Vrací:**
float[]