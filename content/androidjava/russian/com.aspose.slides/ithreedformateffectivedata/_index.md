---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides для Android через справочник Java API
description: Неизменяемый объект, представляющий эффективные свойства 3-D форматирования.
type: docs
url: /ru/com.aspose.slides/ithreedformateffectivedata/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

Неизменяемый объект, представляющий эффективные свойства 3-D форматирования.

--------------------

Этот интерфейс используется вместе с интерфейсом [IThreeDFormat](../../com.aspose.slides/ithreedformat) для возврата эффективных значений форматирования с применением наследования.
## Методы

| Метод | Описание |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Возвращает ширину 3D контура. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Возвращает высоту эффекта выдавливания. |
| [getDepth()](#getDepth--) | Возвращает глубину 3D формы. |
| [getBevelTop()](#getBevelTop--) | Возвращает тип верхней 3D фаски. |
| [getBevelBottom()](#getBevelBottom--) | Возвращает тип нижней 3D фаски. |
| [getContourColor()](#getContourColor--) | Возвращает цвет контура. |
| [getExtrusionColor()](#getExtrusionColor--) | Возвращает цвет выдавливания. |
| [getCamera()](#getCamera--) | Возвращает настройки камеры. |
| [getLightRig()](#getLightRig--) | Возвращает тип освещения. |
| [getMaterial()](#getMaterial--) | Возвращает тип материала. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```


Возвращает ширину 3D контура. Только для чтения double.

**Возвращаемое значение:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```


Возвращает высоту эффекта выдавливания. Только для чтения double.

**Возвращаемое значение:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```


Возвращает глубину 3D формы. Только для чтения double.

**Возвращаемое значение:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```


Возвращает тип верхней 3D фаски. Только для чтения [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Возвращаемое значение:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```


Возвращает тип нижней 3D фаски. Только для чтения [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Возвращаемое значение:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Integer getContourColor()
```


Возвращает цвет контура. Только для чтения java.lang.Integer.

**Возвращаемое значение:**
java.lang.Integer
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Integer getExtrusionColor()
```


Возвращает цвет выдавливания. Только для чтения java.lang.Integer.

**Возвращаемое значение:**
java.lang.Integer
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```


Возвращает настройки камеры. Только для чтения [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**Возвращаемое значение:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```


Возвращает тип освещения. Только для чтения [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**Возвращаемое значение:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


Возвращает тип материала. Только для чтения [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Возвращаемое значение:**
int