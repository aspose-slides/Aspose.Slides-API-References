---
title: IThreeDFormat
second_title: Справочник API Aspose.Slides для Android через Java
description: Представляет свойства 3-D.
type: docs
url: /ru/com.aspose.slides/ithreedformat/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

Представляет свойства 3-D.
## Методы

| Метод | Описание |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Возвращает или задаёт ширину 3D контура. |
| [setContourWidth(double value)](#setContourWidth-double-) | Возвращает или задаёт ширину 3D контура. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Возвращает или задаёт высоту эффекта выдавливания. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Возвращает или задаёт высоту эффекта выдавливания. |
| [getDepth()](#getDepth--) | Возвращает или задаёт глубину 3D фигуры. |
| [setDepth(double value)](#setDepth-double-) | Возвращает или задаёт глубину 3D фигуры. |
| [getBevelTop()](#getBevelTop--) | Возвращает или задаёт тип верхней 3D фаски. |
| [getBevelBottom()](#getBevelBottom--) | Возвращает или задаёт тип нижней 3D фаски. |
| [getContourColor()](#getContourColor--) | Возвращает или задаёт цвет контура. |
| [getExtrusionColor()](#getExtrusionColor--) | Возвращает или задаёт цвет выдавливания. |
| [getCamera()](#getCamera--) | Возвращает или задаёт параметры камеры. |
| [getLightRig()](#getLightRig--) | Возвращает или задаёт тип света. |
| [getMaterial()](#getMaterial--) | Возвращает или задаёт тип материала. |
| [setMaterial(int value)](#setMaterial-int-) | Возвращает или задаёт тип материала. |
| [getEffective()](#getEffective--) | Получает эффективные данные 3-D форматирования с учётом наследования. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Возвращает или задаёт ширину 3D контура. Чтение/запись double.

**Возвращаемое значение:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```

Возвращает или задаёт ширину 3D контура. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Возвращает или задаёт высоту эффекта выдавливания. Чтение/запись double.

**Возвращаемое значение:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```

Возвращает или задаёт высоту эффекта выдавливания. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

Возвращает или задаёт глубину 3D фигуры. Чтение/запись double.

**Возвращаемое значение:**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```

Возвращает или задаёт глубину 3D фигуры. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```

Возвращает или задаёт тип верхней 3D фаски. Только чтение [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Возвращаемое значение:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```

Возвращает или задаёт тип нижней 3D фаски. Только чтение [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Возвращаемое значение:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```

Возвращает или задаёт цвет контура. Только чтение [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```

Возвращает или задаёт цвет выдавливания. Только чтение [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```

Возвращает или задаёт параметры камеры. Только чтение [ICamera](../../com.aspose.slides/icamera).

**Возвращаемое значение:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```

Возвращает или задаёт тип света. Только чтение [ILightRig](../../com.aspose.slides/ilightrig).

**Возвращаемое значение:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Возвращает или задаёт тип материала. Чтение/запись [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Возвращаемое значение:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```

Возвращает или задаёт тип материала. Чтение/запись [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```

Получает эффективные данные 3-D форматирования с учётом наследования.

**Возвращаемое значение:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).