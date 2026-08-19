---
title: IThreeDFormat
second_title: Aspose.Slides pro Java – reference API
description: Zastupuje 3-D vlastnosti.
type: docs
url: /cs/com.aspose.slides/ithreedformat/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

Zastupuje 3-D vlastnosti.
## Metody

| Metoda | Popis |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Vrací nebo nastavuje šířku 3D kontury. |
| [setContourWidth(double value)](#setContourWidth-double-) | Vrací nebo nastavuje šířku 3D kontury. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Vrací nebo nastavuje výšku efektu extruze. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Vrací nebo nastavuje výšku efektu extruze. |
| [getDepth()](#getDepth--) | Vrací nebo nastavuje hloubku 3D objektu. |
| [setDepth(double value)](#setDepth-double-) | Vrací nebo nastavuje hloubku 3D objektu. |
| [getBevelTop()](#getBevelTop--) | Vrací nebo nastavuje typ horního 3D zkosení. |
| [getBevelBottom()](#getBevelBottom--) | Vrací nebo nastavuje typ spodního 3D zkosení. |
| [getContourColor()](#getContourColor--) | Vrací nebo nastavuje barvu kontury. |
| [getExtrusionColor()](#getExtrusionColor--) | Vrací nebo nastavuje barvu extruze. |
| [getCamera()](#getCamera--) | Vrací nebo nastavuje nastavení kamery. |
| [getLightRig()](#getLightRig--) | Vrací nebo nastavuje typ světla. |
| [getMaterial()](#getMaterial--) | Vrací nebo nastavuje typ materiálu. |
| [setMaterial(int value)](#setMaterial-int-) | Vrací nebo nastavuje typ materiálu. |
| [getEffective()](#getEffective--) | Získá efektivní data formátování 3-D s aplikovaným děděním. |

### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Vrací nebo nastavuje šířku 3D kontury. Čtení/zápis double.

**Vrací:**
double

### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```

Vrací nebo nastavuje šířku 3D kontury. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Vrací nebo nastavuje výšku efektu extruze. Čtení/zápis double.

**Vrací:**
double

### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```

Vrací nebo nastavuje výšku efektu extruze. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

Vrací nebo nastavuje hloubku 3D objektu. Čtení/zápis double.

**Vrací:**
double

### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```

Vrací nebo nastavuje hloubku 3D objektu. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```

Vrací nebo nastavuje typ horního 3D zkosení. Pouze pro čtení [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Vrací:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)

### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```

Vrací nebo nastavuje typ spodního 3D zkosení. Pouze pro čtení [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Vrací:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)

### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```

Vrací nebo nastavuje barvu kontury. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```

Vrací nebo nastavuje barvu extruze. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```

Vrací nebo nastavuje nastavení kamery. Pouze pro čtení [ICamera](../../com.aspose.slides/icamera).

**Vrací:**
[ICamera](../../com.aspose.slides/icamera)

### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```

Vrací nebo nastavuje typ světla. Pouze pro čtení [ILightRig](../../com.aspose.slides/ilightrig).

**Vrací:**
[ILightRig](../../com.aspose.slides/ilightrig)

### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Vrací nebo nastavuje typ materiálu. Čtení/zápis [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Vrací:**
int

### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```

Vrací nebo nastavuje typ materiálu. Čtení/zápis [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```

Získá efektivní data formátování 3-D s aplikovaným děděním.

**Vrací:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).