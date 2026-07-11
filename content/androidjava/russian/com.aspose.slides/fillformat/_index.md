---
title: FillFormat
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет параметры форматирования заливки.
type: docs
url: /ru/com.aspose.slides/fillformat/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Все реализованные интерфейсы:**
[com.aspose.slides.IFillFormat](../../com.aspose.slides/ifillformat)
```
public final class FillFormat extends PVIObject implements IFillFormat
```

Представляет параметры форматирования заливки.
## Методы

| Метод | Описание |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Возвращает или задаёт тип заливки. |
| [setFillType(byte value)](#setFillType-byte-) | Возвращает или задаёт тип заливки. |
| [getSolidFillColor()](#getSolidFillColor--) | Возвращает цвет заливки. |
| [getGradientFormat()](#getGradientFormat--) | Возвращает формат градиентной заливки. |
| [getPatternFormat()](#getPatternFormat--) | Возвращает формат узорной заливки. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Возвращает формат заливки изображением. |
| [getRotateWithShape()](#getRotateWithShape--) | Определяет, следует ли вращать заливку вместе с фигурой. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Определяет, следует ли вращать заливку вместе с фигурой. |
| [getEffective()](#getEffective--) | Получает данные эффективного форматирования заливки с учётом наследования. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Версия. Только для чтения long.

**Возвращает:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```

Возвращает или задаёт тип заливки. Чтение/запись [FillType](../../com.aspose.slides/filltype).

**Возвращает:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

Возвращает или задаёт тип заливки. Чтение/запись [FillType](../../com.aspose.slides/filltype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

Возвращает цвет заливки. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

Возвращает формат градиентной заливки. Только для чтения [IGradientFormat](../../com.aspose.slides/igradientformat).

**Возвращает:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

Возвращает формат узорной заливки. Только для чтения [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Возвращает:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public final IPictureFillFormat getPictureFillFormat()
```

Возвращает формат заливки изображением. Только для чтения [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Возвращает:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

Определяет, следует ли вращать заливку вместе с фигурой. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

Определяет, следует ли вращать заливку вместе с фигурой. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public final IFillFormatEffectiveData getEffective()
```

Получает данные эффективного форматирования заливки с учётом наследования.

--------------------

> ```
> This example demonstrates getting shape's effective fill format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IFillFormatEffectiveData effectiveFillFormat = pres.getSlides().get_Item(0).getShapes().get_Item(0).getFillFormat().getEffective();
>  	System.out.println("Type: " + effectiveFillFormat.getFillType());
>  	switch (effectiveFillFormat.getFillType())
>  	{
>  		case FillType.Solid:
>  			System.out.println("Fill color: " + effectiveFillFormat.getSolidFillColor());
>  			break;
>  		case FillType.Pattern:
>  			System.out.println("Pattern style: " + effectiveFillFormat.getPatternFormat().getPatternStyle());
>  			System.out.println("Fore color: " + effectiveFillFormat.getPatternFormat().getForeColor());
>  			System.out.println("Back color: " + effectiveFillFormat.getPatternFormat().getBackColor());
>  			break;
>  		case FillType.Gradient:
>  			System.out.println("Gradient direction: " + effectiveFillFormat.getGradientFormat().getGradientDirection());
>  			System.out.println("Gradient stops count: " + effectiveFillFormat.getGradientFormat().getGradientStops().size());
>  			break;
>  		case FillType.Picture:
>  			System.out.println("Picture width: " + effectiveFillFormat.getPictureFillFormat().getPicture().getImage().getWidth());
>  			System.out.println("Picture height: " + effectiveFillFormat.getPictureFillFormat().getPicture().getImage().getHeight());
>  			break;
>  	}
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) — [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).