---
title: IThreeDFormatEffectiveData
second_title: Referencja API Aspose.Slides dla Javy
description: Niemutowalny obiekt reprezentujący skuteczne właściwości formatowania 3-D.
type: docs
url: /pl/com.aspose.slides/ithreedformateffectivedata/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

Niemutowalny obiekt reprezentujący skuteczne właściwości formatowania 3-D.

--------------------

Ten interfejs jest używany razem z interfejsem [IThreeDFormat](../../com.aspose.slides/ithreedformat) w celu zwrócenia skutecznych wartości formatowania z zastosowaniem dziedziczenia.
## Metody

| Metoda | Opis |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Zwraca szerokość konturu 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Zwraca wysokość efektu wyciągnięcia. |
| [getDepth()](#getDepth--) | Zwraca głębokość kształtu 3D. |
| [getBevelTop()](#getBevelTop--) | Zwraca typ górnego fazowania 3D. |
| [getBevelBottom()](#getBevelBottom--) | Zwraca typ dolnego fazowania 3D. |
| [getContourColor()](#getContourColor--) | Zwraca kolor konturu. |
| [getExtrusionColor()](#getExtrusionColor--) | Zwraca kolor wyciągnięcia. |
| [getCamera()](#getCamera--) | Zwraca ustawienia kamery. |
| [getLightRig()](#getLightRig--) | Zwraca typ światła. |
| [getMaterial()](#getMaterial--) | Zwraca typ materiału. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```


Zwraca szerokość konturu 3D. Tylko do odczytu double.

**Zwraca:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```


Zwraca wysokość efektu wyciągnięcia. Tylko do odczytu double.

**Zwraca:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```


Zwraca głębokość kształtu 3D. Tylko do odczytu double.

**Zwraca:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```


Zwraca typ górnego fazowania 3D. Tylko do odczytu [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Zwraca:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```


Zwraca typ dolnego fazowania 3D. Tylko do odczytu [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Zwraca:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Color getContourColor()
```


Zwraca kolor konturu. Tylko do odczytu java.awt.Color.

**Zwraca:**
java.awt.Color
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Color getExtrusionColor()
```


Zwraca kolor wyciągnięcia. Tylko do odczytu java.awt.Color.

**Zwraca:**
java.awt.Color
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```


Zwraca ustawienia kamery. Tylko do odczytu [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**Zwraca:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```


Zwraca typ światła. Tylko do odczytu [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**Zwraca:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


Zwraca typ materiału. Tylko do odczytu [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Zwraca:**
int