---
title: IFillFormatEffectiveData
second_title: Справочник API Aspose.Slides для Java
description: Неизменяемый объект, содержащий эффективные свойства форматирования заполнения.
type: docs
url: /ru/com.aspose.slides/ifillformateffectivedata/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

Неизменяемый объект, содержащий эффективные свойства заполнения.

--------------------

Этот интерфейс используется совместно с интерфейсом [IFillFormat](../../com.aspose.slides/ifillformat) для получения эффективных значений форматирования с применением наследования.
## Методы

| Method | Description |
| --- | --- |
| [getFillType()](#getFillType--) | Возвращает тип заполнения. |
| [getSolidFillColor()](#getSolidFillColor--) | Возвращает цвет заполнения. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | Возвращает цвет заполнения, определённый цветовой схемой. |
| [getGradientFormat()](#getGradientFormat--) | Возвращает формат градиентного заполнения. |
| [getPatternFormat()](#getPatternFormat--) | Возвращает формат узорного заполнения. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Возвращает формат заполнения изображением. |
| [getRotateWithShape()](#getRotateWithShape--) | Определяет, будет ли заполнение вращаться вместе с фигурой. |
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


Возвращает цвет заполнения. Только для чтения java.awt.Color.

**Возвращает:**
java.awt.Color
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```


Возвращает цвет заполнения, определённый цветовой схемой. Значение [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) указывает, что SolidFillColor (\#getSolidFillColor.getSolidFillColor) не является цветом схемы. Только для чтения [SchemeColor](../../com.aspose.slides/schemecolor).

**Возвращает:**
int
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


Возвращает формат узорного заполнения. Только для чтения [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Возвращает:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```


Возвращает формат заполнения изображением. Только для чтения [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**Возвращает:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Определяет, будет ли заполнение вращаться вместе с фигурой. Только для чтения boolean.

**Возвращает:**
boolean