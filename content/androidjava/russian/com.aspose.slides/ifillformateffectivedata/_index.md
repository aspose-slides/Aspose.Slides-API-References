---
title: IFillFormatEffectiveData
second_title: Aspose.Slides для Android через справку по Java API
description: Неизменяемый объект, содержащий эффективные свойства форматирования заливки.
type: docs
url: /ru/com.aspose.slides/ifillformateffectivedata/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

Неизменяемый объект, содержащий эффективные свойства форматирования заливки.

--------------------

Этот интерфейс используется вместе с интерфейсом [IFillFormat](../../com.aspose.slides/ifillformat) для возврата эффективных значений форматирования с применением наследования.
## Методы

| Метод | Описание |
| --- | --- |
| [getFillType()](#getFillType--) | Возвращает тип заливки. |
| [getSolidFillColor()](#getSolidFillColor--) | Возвращает цвет заливки. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | Получает цвет заливки, определённый схемой цветов. |
| [getGradientFormat()](#getGradientFormat--) | Возвращает формат градиентной заливки. |
| [getPatternFormat()](#getPatternFormat--) | Возвращает формат узорной заливки. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Возвращает формат заливки изображением. |
| [getRotateWithShape()](#getRotateWithShape--) | Определяет, должна ли заливка вращаться вместе с фигурой. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Возвращает тип заливки. Только для чтения [FillType](../../com.aspose.slides/filltype).

**Возвращает:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```


Возвращает цвет заливки. Только для чтения java.lang.Integer.

**Возвращает:**
java.lang.Integer
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```


Получает цвет заливки, определённый схемой цветов. Значение [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) указывает, что SolidFillColor (\#getSolidFillColor.getSolidFillColor) не является цветом схемы. Только для чтения [SchemeColor](../../com.aspose.slides/schemecolor).

**Возвращает:**
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Возвращает формат градиентной заливки. Только для чтения [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Возвращает:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Возвращает формат узорной заливки. Только для чтения [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Возвращает:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```


Возвращает формат заливки изображением. Только для чтения [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**Возвращает:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Определяет, должна ли заливка вращаться вместе с фигурой. Только для чтения boolean.

**Возвращает:**
boolean