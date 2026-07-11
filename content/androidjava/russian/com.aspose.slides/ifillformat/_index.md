---
title: IFillFormat
second_title: Aspose.Slides для Android через справочник API Java
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

| Method | Description |
| --- | --- |
| [getFillType()](#getFillType--) | Возвращает или задает тип заливки. |
| [setFillType(byte value)](#setFillType-byte-) | Возвращает или задает тип заливки. |
| [getSolidFillColor()](#getSolidFillColor--) | Возвращает цвет заливки. |
| [getGradientFormat()](#getGradientFormat--) | Возвращает формат градиентной заливки. |
| [getPatternFormat()](#getPatternFormat--) | Возвращает формат заливки узором. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Возвращает формат заливки изображением. |
| [getRotateWithShape()](#getRotateWithShape--) | Определяет, должна ли заливка вращаться вместе с фигурой. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Определяет, должна ли заливка вращаться вместе с фигурой. |
| [getEffective()](#getEffective--) | Получает данные эффективного форматирования заливки с применённым наследованием. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Возвращает или задает тип заливки. Чтение/запись [FillType](../../com.aspose.slides/filltype).

**Возвращает:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

Возвращает или задает тип заливки. Чтение/запись [FillType](../../com.aspose.slides/filltype).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

Возвращает цвет заливки. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

Возвращает формат градиентной заливки. Только для чтения [IGradientFormat](../../com.aspose.slides/igradientformat).

**Возвращает:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

Возвращает формат заливки узором. Только для чтения [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Возвращает:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```

Возвращает формат заливки изображением. Только для чтения [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Возвращает:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

Определяет, должна ли заливка вращаться вместе с фигурой. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

Определяет, должна ли заливка вращаться вместе с фигурой. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```

Получает данные эффективного форматирования заливки с применённым наследованием.

**Возвращает:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) — [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).