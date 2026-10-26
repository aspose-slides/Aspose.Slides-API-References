---
title: IColorEffect
second_title: Справочник API Aspose.Slides для Java
description: Представляет цветовой эффект для анимационного поведения.
type: docs
url: /ru/com.aspose.slides/icoloreffect/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IColorEffect extends IBehavior
```

Представляет цветовой эффект для анимационного поведения.
## Методы

| Метод | Описание |
| --- | --- |
| [getFrom()](#getFrom--) | Это значение используется для указания начального цвета поведения. |
| [setFrom(IColorFormat value)](#setFrom-com.aspose.slides.IColorFormat-) | Это значение используется для указания начального цвета поведения. |
| [getTo()](#getTo--) | Описывает получаемый цвет при изменении цвета анимации. |
| [setTo(IColorFormat value)](#setTo-com.aspose.slides.IColorFormat-) | Описывает получаемый цвет при изменении цвета анимации. |
| [getBy()](#getBy--) | Описывает относительное значение смещения для цветовой анимации. |
| [setBy(IColorOffset value)](#setBy-com.aspose.slides.IColorOffset-) | Описывает относительное значение смещения для цветовой анимации. |
| [getColorSpace()](#getColorSpace--) | Представляет цветовое пространство поведения. |
| [setColorSpace(int value)](#setColorSpace-int-) | Представляет цветовое пространство поведения. |
| [getDirection()](#getDirection--) | Указывает, в каком направлении циклически вращать оттенок по цветовому кругу. |
| [setDirection(int value)](#setDirection-int-) | Указывает, в каком направлении циклически вращать оттенок по цветовому кругу. |
### getFrom() {#getFrom--}
```
public abstract IColorFormat getFrom()
```

Это значение используется для указания начального цвета поведения. Чтение/запись [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setFrom(IColorFormat value) {#setFrom-com.aspose.slides.IColorFormat-}
```
public abstract void setFrom(IColorFormat value)
```

Это значение используется для указания начального цвета поведения. Чтение/запись [IColorFormat](../../com.aspose.slides/icolorformat).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getTo() {#getTo--}
```
public abstract IColorFormat getTo()
```

Описывает получаемый цвет при изменении цвета анимации. Чтение/запись [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setTo(IColorFormat value) {#setTo-com.aspose.slides.IColorFormat-}
```
public abstract void setTo(IColorFormat value)
```

Описывает получаемый цвет при изменении цвета анимации. Чтение/запись [IColorFormat](../../com.aspose.slides/icolorformat).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getBy() {#getBy--}
```
public abstract IColorOffset getBy()
```

Описывает относительное значение смещения для цветовой анимации. Чтение/запись [IColorOffset](../../com.aspose.slides/icoloroffset).

**Возвращаемое значение:**
[IColorOffset](../../com.aspose.slides/icoloroffset)
### setBy(IColorOffset value) {#setBy-com.aspose.slides.IColorOffset-}
```
public abstract void setBy(IColorOffset value)
```

Описывает относительное значение смещения для цветовой анимации. Чтение/запись [IColorOffset](../../com.aspose.slides/icoloroffset).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IColorOffset](../../com.aspose.slides/icoloroffset) |  |

### getColorSpace() {#getColorSpace--}
```
public abstract int getColorSpace()
```

Представляет цветовое пространство поведения. Чтение/запись [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Возвращаемое значение:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public abstract void setColorSpace(int value)
```

Представляет цветовое пространство поведения. Чтение/запись [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Указывает, в каком направлении циклически вращать оттенок по цветовому кругу. Чтение/запись [ColorDirection](../../com.aspose.slides/colordirection).

**Возвращаемое значение:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Указывает, в каком направлении циклически вращать оттенок по цветовому кругу. Чтение/запись [ColorDirection](../../com.aspose.slides/colordirection).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |