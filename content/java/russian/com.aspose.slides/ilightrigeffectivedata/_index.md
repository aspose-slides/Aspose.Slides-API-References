---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Неизменяемый объект, содержащий эффективные свойства светового устройства.
type: docs
url: /ru/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Неизменяемый объект, содержащий эффективные свойства светового устройства.

--------------------

Этот интерфейс используется как часть [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Методы

| Метод | Описание |
| --- | --- |
| [getDirection()](#getDirection--) | Light direction. |
| [getLightType()](#getLightType--) | Represents a preset light right that can be applied to a shape. |
| [getRotation()](#getRotation--) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Направление света. Только для чтения [LightingDirection](../../com.aspose.slides/lightingdirection).

**Возвращает:**
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Представляет заданный тип света, который можно применить к фигуре. Световой набор представляет собой группу светильников, ориентированных определенным образом относительно 3D-сцены. Только для чтения [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Возвращает:**
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Вращение определяется с использованием широтной координаты, долготной координаты и оборота вокруг оси в качестве широтной и долготной координат. Первый элемент в возвращаемом массиве — широта, второй — долгота, третий — оборот.

**Возвращает:**
float[] - Координаты вращения как float[]