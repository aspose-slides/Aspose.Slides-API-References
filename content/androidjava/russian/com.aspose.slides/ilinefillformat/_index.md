---
title: ILineFillFormat
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет свойства заполнения линий.
type: docs
url: /ru/com.aspose.slides/ilinefillformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

Represents properties for lines filling.
## Методы

| Method | Description |
| --- | --- |
| [getFillType()](#getFillType--) | Возвращает или задаёт тип заливки. |
| [setFillType(byte value)](#setFillType-byte-) | Возвращает или задаёт тип заливки. |
| [getSolidFillColor()](#getSolidFillColor--) | Возвращает цвет сплошного заливки. |
| [getGradientFormat()](#getGradientFormat--) | Возвращает формат градиентного заливания. |
| [getPatternFormat()](#getPatternFormat--) | Возвращает формат шаблонного заливания. |
| [getRotateWithShape()](#getRotateWithShape--) | Определяет, следует ли вращать заливку вместе с фигурой. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Определяет, следует ли вращать заливку вместе с фигурой. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Возвращает или задаёт тип заливки. Чтение/запись [FillType](../../com.aspose.slides/filltype).

**Возвращаемое значение:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

Возвращает или задаёт тип заливки. Чтение/запись [FillType](../../com.aspose.slides/filltype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

Возвращает цвет сплошного заливки. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

Возвращает формат градиентного заливания. Только для чтения [IGradientFormat](../../com.aspose.slides/igradientformat).

**Возвращаемое значение:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

Возвращает формат шаблонного заливания. Только для чтения [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Возвращаемое значение:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

Определяет, следует ли вращать заливку вместе с фигурой. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

Определяет, следует ли вращать заливку вместе с фигурой. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |