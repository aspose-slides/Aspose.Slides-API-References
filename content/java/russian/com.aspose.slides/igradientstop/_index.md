---
title: IGradientStop
second_title: Aspose.Slides for Java API Reference
description: Represents a gradient format.
type: docs
url: /ru/com.aspose.slides/igradientstop/
---```
public interface IGradientStop
```

Представляет формат градиента.

## Методы

| Метод | Описание |
| --- | --- |
| [getPosition()](#getPosition--) | Возвращает или задает позицию (0..1) градиентного стопа. |
| [setPosition(float value)](#setPosition-float-) | Возвращает или задает позицию (0..1) градиентного стопа. |
| [getColor()](#getColor--) | Возвращает цвет градиентного стопа. |

### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

Возвращает или задает позицию (0..1) градиентного стопа. Чтение/запись float.

**Возвращает:**
float

### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

Возвращает или задает позицию (0..1) градиентного стопа. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Возвращает цвет градиентного стопа. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)