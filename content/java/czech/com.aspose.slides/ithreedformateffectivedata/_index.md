---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides pro Java API Reference
description: Neměnný objekt, který představuje efektivní 3-D formátovací vlastnosti.
type: docs
url: /cs/com.aspose.slides/ithreedformateffectivedata/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

Neměnný objekt představující efektivní 3-D formátovací vlastnosti.

--------------------

Toto rozhraní se používá společně s rozhraním [IThreeDFormat](../../com.aspose.slides/ithreedformat) k vrácení efektivních hodnot formátování s aplikovaným děděním.
## Metody

| Metoda | Popis |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Vrací šířku 3D kontury. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Vrací výšku efektu extruze. |
| [getDepth()](#getDepth--) | Vrací hloubku 3D tvaru. |
| [getBevelTop()](#getBevelTop--) | Vrací typ horního 3D zkosení. |
| [getBevelBottom()](#getBevelBottom--) | Vrací typ spodního 3D zkosení. |
| [getContourColor()](#getContourColor--) | Vrací barvu kontury. |
| [getExtrusionColor()](#getExtrusionColor--) | Vrací barvu extruze. |
| [getCamera()](#getCamera--) | Vrací nastavení kamery. |
| [getLightRig()](#getLightRig--) | Vrací typ světla. |
| [getMaterial()](#getMaterial--) | Vrací typ materiálu. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Vrací šířku 3D kontury. Pouze pro čtení double.

**Vrací:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Vrací výšku efektu extruze. Pouze pro čtení double.

**Vrací:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

Vrací hloubku 3D tvaru. Pouze pro čtení double.

**Vrací:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```

Vrací typ horního 3D zkosení. Pouze pro čtení [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Vrací:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```

Vrací typ spodního 3D zkosení. Pouze pro čtení [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Vrací:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Color getContourColor()
```

Vrací barvu kontury. Pouze pro čtení java.awt.Color.

**Vrací:**
java.awt.Color
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Color getExtrusionColor()
```

Vrací barvu extruze. Pouze pro čtení java.awt.Color.

**Vrací:**
java.awt.Color
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```

Vrací nastavení kamery. Pouze pro čtení [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**Vrací:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```

Vrací typ světla. Pouze pro čtení [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**Vrací:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Vrací typ materiálu. Pouze pro čtení [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Vrací:**
int