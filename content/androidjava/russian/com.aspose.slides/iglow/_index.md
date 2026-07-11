---
title: IGlow
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет эффект свечения, при котором размытый цветной контур добавляется за пределами границ объекта.
type: docs
url: /ru/com.aspose.slides/iglow/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

Представляет эффект свечения, при котором размытый цветной контур добавляется за пределами границ объекта.
## Методы

| Метод | Описание |
| --- | --- |
| [getRadius()](#getRadius--) | Радиус. |
| [setRadius(double value)](#setRadius-double-) | Радиус. |
| [getColor()](#getColor--) | Формат цвета. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Радиус. Чтение/запись double.

**Возвращаемое значение:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

Радиус. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Формат цвета. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)