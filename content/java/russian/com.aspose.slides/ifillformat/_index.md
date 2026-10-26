---
title: IFillFormat
second_title: Справочник API Aspose.Slides для Java
description: Представляет параметры форматирования заливки.
type: docs
url: /ru/com.aspose.slides/ifillformat/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

Представляет параметры форматирования заливки.
## Методы

| Метод | Описание |
| --- | --- |
| [getFillType()](#getFillType--) | Возвращает или задает тип заливки. |
| [setFillType(byte value)](#setFillType-byte-) | Возвращает или задает тип заливки. |
| [getSolidFillColor()](#getSolidFillColor--) | Возвращает цвет заливки. |
| [getGradientFormat()](#getGradientFormat--) | Возвращает формат градиентной заливки. |
| [getPatternFormat()](#getPatternFormat--) | Возвращает формат узорчатой заливки. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Возвращает формат заливки изображением. |
| [getRotateWithShape()](#getRotateWithShape--) | Определяет, должна ли заливка вращаться вместе с фигурой. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Определяет, должна ли заливка вращаться вместе с фигурой. |
| [getEffective()](#getEffective--) | Получает данные эффективного форматирования заливки с учётом наследования. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Возвращает или задает тип заливки. Чтение/запись [FillType](../../com.aspose.slides/filltype).

**Возвращаемое значение:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

Возвращает или задает тип заливки. Чтение/запись [FillType](../../com.aspose.slides/filltype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

Возвращает цвет заливки. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

Возвращает формат градиентной заливки. Только для чтения [IGradientFormat](../../com.aspose.slides/igradientformat).

**Возвращаемое значение:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

Возвращает формат узорчатой заливки. Только для чтения [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Возвращаемое значение:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```

Возвращает формат заливки изображением. Только для чтения [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Возвращаемое значение:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

Определяет, должна ли заливка вращаться вместе с фигурой. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

Определяет, должна ли заливка вращаться вместе с фигурой. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```

Получает данные эффективного форматирования заливки с учётом наследования.

**Возвращаемое значение:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - A [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).