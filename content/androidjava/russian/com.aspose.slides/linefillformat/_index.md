---
title: LineFillFormat
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет свойства для заполнения линий.
type: docs
url: /ru/com.aspose.slides/linefillformat/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Все реализованные интерфейсы:**
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

Представляет свойства для заполнения линий.
## Методы

| Метод | Описание |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Возвращает или задает тип заполнения. |
| [setFillType(byte value)](#setFillType-byte-) | Возвращает или задает тип заполнения. |
| [getRotateWithShape()](#getRotateWithShape--) | Определяет, следует ли поворачивать заполнение вместе с фигурой. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Определяет, следует ли поворачивать заполнение вместе с фигурой. |
| [getSolidFillColor()](#getSolidFillColor--) | Возвращает цвет сплошного заполнения. |
| [getGradientFormat()](#getGradientFormat--) | Возвращает формат градиентного заполнения. |
| [getPatternFormat()](#getPatternFormat--) | Возвращает формат узорного заполнения. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Версия. Только для чтения long.

**Возвращаемое значение:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```

Возвращает или задает тип заполнения. Чтение/запись [FillType](../../com.aspose.slides/filltype).

**Возвращаемое значение:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

Возвращает или задает тип заполнения. Чтение/запись [FillType](../../com.aspose.slides/filltype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

Определяет, следует ли поворачивать заполнение вместе с фигурой. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

Определяет, следует ли поворачивать заполнение вместе с фигурой. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

Возвращает цвет сплошного заполнения. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

Возвращает формат градиентного заполнения. Только для чтения [IGradientFormat](../../com.aspose.slides/igradientformat).

**Возвращаемое значение:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

Возвращает формат узорного заполнения. Только для чтения [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Возвращаемое значение:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)