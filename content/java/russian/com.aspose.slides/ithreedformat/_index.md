---
title: IThreeDFormat
second_title: Aspose.Slides для Java API Reference
description: Представляет 3-D свойства.
type: docs
url: /ru/com.aspose.slides/ithreedformat/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

Представляет 3-D свойства.
## Методы

| Метод | Описание |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Возвращает или задает ширину 3D контура. |
| [setContourWidth(double value)](#setContourWidth-double-) | Возвращает или задает ширину 3D контура. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Возвращает или задает высоту эффекта экструзии. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Возвращает или задает высоту эффекта экструзии. |
| [getDepth()](#getDepth--) | Возвращает или задает глубину 3D формы. |
| [setDepth(double value)](#setDepth-double-) | Возвращает или задает глубину 3D формы. |
| [getBevelTop()](#getBevelTop--) | Возвращает или задает тип верхней 3D фаски. |
| [getBevelBottom()](#getBevelBottom--) | Возвращает или задает тип нижней 3D фаски. |
| [getContourColor()](#getContourColor--) | Возвращает или задает цвет контура. |
| [getExtrusionColor()](#getExtrusionColor--) | Возвращает или задает цвет экструзии. |
| [getCamera()](#getCamera--) | Возвращает или задает настройки камеры. |
| [getLightRig()](#getLightRig--) | Возвращает или задает тип света. |
| [getMaterial()](#getMaterial--) | Возвращает или задает тип материала. |
| [setMaterial(int value)](#setMaterial-int-) | Возвращает или задает тип материала. |
| [getEffective()](#getEffective--) | Получает эффективные данные 3-D форматирования с учётом наследования. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Возвращает или задает ширину 3D контура. Чтение/запись double.

**Возвращаемое значение:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```

Возвращает или задает ширину 3D контура. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Возвращает или задает высоту эффекта экструзии. Чтение/запись double.

**Возвращаемое значение:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```

Возвращает или задает высоту эффекта экструзии. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

Возвращает или задает глубину 3D формы. Чтение/запись double.

**Возвращаемое значение:**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```

Возвращает или задает глубину 3D формы. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```

Возвращает или задает тип верхней 3D фаски. Только для чтения [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Возвращаемое значение:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```

Возвращает или задает тип нижней 3D фаски. Только для чтения [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Возвращаемое значение:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```

Возвращает или задает цвет контура. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```

Возвращает или задает цвет экструзии. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```

Возвращает или задает настройки камеры. Только для чтения [ICamera](../../com.aspose.slides/icamera).

**Возвращаемое значение:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```

Возвращает или задает тип света. Только для чтения [ILightRig](../../com.aspose.slides/ilightrig).

**Возвращаемое значение:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Возвращает или задает тип материала. Чтение/запись [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Возвращаемое значение:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```

Возвращает или задает тип материала. Чтение/запись [MaterialPresetType](../../com.aspose.slides/materialpresettype).

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