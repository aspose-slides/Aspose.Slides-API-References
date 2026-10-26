---
title: IBlur
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет эффект размытия, который применяется ко всей фигуре, включая её заливку.
type: docs
url: /ru/com.aspose.slides/iblur/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Представляет эффект размытия, применяемый ко всей фигуре, включая её заливку. Все цветовые каналы, включая альфа-канал, затронуты.

## Методы

| Метод | Описание |
| --- | --- |
| [getRadius()](#getRadius--) | Возвращает или задает радиус размытия. |
| [setRadius(double value)](#setRadius-double-) | Возвращает или задает радиус размытия. |
| [getGrow()](#getGrow--) | Определяет, должны ли границы объекта расширяться в результате размытия. |
| [setGrow(boolean value)](#setGrow-boolean-) | Определяет, должны ли границы объекта расширяться в результате размытия. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Возвращает или задает радиус размытия. Чтение/запись double.

**Возвращаемое значение:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

Возвращает или задает радиус размытия. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Определяет, должны ли границы объекта расширяться в результате размытия. True указывает, что границы расширяются, а false — что нет. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```

Определяет, должны ли границы объекта расширяться в результате размытия. True указывает, что границы расширяются, а false — что нет. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |