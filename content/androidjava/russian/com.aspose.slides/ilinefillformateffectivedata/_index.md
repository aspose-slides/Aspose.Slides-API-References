---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides для Android через Java API Reference
description: Неизменяемый объект, содержащий свойства эффективного заполнения линий.
type: docs
url: /ru/com.aspose.slides/ilinefillformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Неизменяемый объект, содержащий свойства эффективного заполнения линий.

--------------------

Этот интерфейс используется как часть [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
## Методы

| Метод | Описание |
| --- | --- |
| [getFillType()](#getFillType--) | Возвращает тип заливки. |
| [getSolidFillColor()](#getSolidFillColor--) | Возвращает цвет сплошной заливки. |
| [getGradientFormat()](#getGradientFormat--) | Возвращает формат градиентной заливки. |
| [getPatternFormat()](#getPatternFormat--) | Возвращает формат узорной заливки. |
| [getRotateWithShape()](#getRotateWithShape--) | Определяет, должна ли заливка вращаться вместе с фигурой. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Возвращает тип заливки. Только для чтения [FillType](../../com.aspose.slides/filltype).

**Returns:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```


Возвращает цвет сплошной заливки. Только для чтения java.lang.Integer.

**Returns:**
java.lang.Integer
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Возвращает формат градиентной заливки. Только для чтения [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Returns:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Возвращает формат узорной заливки. Только для чтения [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Returns:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Определяет, должна ли заливка вращаться вместе с фигурой. Только для чтения boolean.

**Returns:**
boolean