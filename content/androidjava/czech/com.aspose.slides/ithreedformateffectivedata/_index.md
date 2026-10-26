---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides pro Android pomocí reference Java API
description: Neměnný objekt, který představuje efektivní 3-D formátovací vlastnosti.
type: docs
url: /cs/com.aspose.slides/ithreedformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

Neměnný objekt, který představuje efektivní 3-D formátovací vlastnosti.

--------------------

Toto rozhraní se používá společně s rozhraním [IThreeDFormat](../../com.aspose.slides/ithreedformat) k vrácení efektivních formátovacích hodnot s aplikovaným děděním.

## Metody

| Metoda | Popis |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Vrací šířku 3D kontury. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Vrací výšku extrudovaného efektu. |
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


Vrací šířku 3D kontury. Pouze ke čtení double.

**Vrací:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```


Vrací výšku extrudovaného efektu. Pouze ke čtení double.

**Vrací:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```


Vrací hloubku 3D tvaru. Pouze ke čtení double.

**Vrací:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```


Vrací typ horního 3D zkosení. Pouze ke čtení [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Vrací:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```


Vrací typ spodního 3D zkosení. Pouze ke čtení [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Vrací:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Integer getContourColor()
```


Vrací barvu kontury. Pouze ke čtení java.lang.Integer.

**Vrací:**
java.lang.Integer
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Integer getExtrusionColor()
```


Vrací barvu extruze. Pouze ke čtení java.lang.Integer.

**Vrací:**
java.lang.Integer
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```


Vrací nastavení kamery. Pouze ke čtení [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**Vrací:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```


Vrací typ světla. Pouze ke čtení [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**Vrací:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


Vrací typ materiálu. Pouze ke čtení [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Vrací:**
int