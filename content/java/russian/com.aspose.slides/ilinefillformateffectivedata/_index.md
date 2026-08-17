---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides для Java – справочник API
description: Неизменяемый объект, содержащий свойства эффективного заполнения линии.
type: docs
url: /ru/com.aspose.slides/ilinefillformateffectivedata/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Неизменяемый объект, содержащий свойства эффективного заполнения линии.

--------------------

Этот интерфейс используется как часть [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
## Методы

| Метод | Описание |
| --- | --- |
| [getFillType()](#getFillType--) | Возвращает тип заполнения. |
| [getSolidFillColor()](#getSolidFillColor--) | Возвращает цвет сплошного заполнения. |
| [getGradientFormat()](#getGradientFormat--) | Возвращает формат градиентного заполнения. |
| [getPatternFormat()](#getPatternFormat--) | Возвращает формат шаблонного заполнения. |
| [getRotateWithShape()](#getRotateWithShape--) | Определяет, должно ли заполнение вращаться вместе с фигурой. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Возвращает тип заполнения. Только для чтения [FillType](../../com.aspose.slides/filltype).

**Возвращает:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```


Возвращает цвет сплошного заполнения. Только для чтения java.awt.Color.

**Возвращает:**
java.awt.Color
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Возвращает формат градиентного заполнения. Только для чтения [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Возвращает:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Возвращает формат шаблонного заполнения. Только для чтения [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Возвращает:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Определяет, должно ли заполнение вращаться вместе с фигурой. Только для чтения boolean.

**Возвращает:**
boolean