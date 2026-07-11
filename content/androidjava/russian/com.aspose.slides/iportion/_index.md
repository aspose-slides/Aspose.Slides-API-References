---
title: IPortion
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет часть текста внутри текстового абзаца.
type: docs
url: /ru/com.aspose.slides/iportion/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

Представляет часть текста внутри текстового абзаца.
## Методы

| Method | Description |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Возвращает объект форматирования, который содержит явно заданные свойства форматирования части текста без применения наследования. |
| [getText()](#getText--) | Получает или задает обычный текст части. |
| [setText(String value)](#setText-java.lang.String-) | Получает или задает обычный текст части. |
| [getField()](#getField--) | Возвращает поле этой части. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Преобразует эту часть в автоматически обновляемое поле. |
| [addField(String internalString)](#addField-java.lang.String-) | Преобразует эту часть в автоматически обновляемое поле. |
| [removeField()](#removeField--) | Преобразует эту часть поля в простую часть. |
| [getRect()](#getRect--) | Получает координаты прямоугольника, ограничивающего часть. |
| [getCoordinates()](#getCoordinates--) | Получает координаты начала части. |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```

Возвращает объект форматирования, который содержит явно заданные свойства форматирования части текста без применения наследования. Только для чтения [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Объект форматирования содержит параметры форматирования, определённые только для текущей части, наследованные данные не применяются.

Чтобы получить эффективные значения, включая наследуемые, используйте метод [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective).

**Возвращаемое значение:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```

Получает или задает обычный текст части. Чтение/запись String.

Value: Текст.

**Возвращаемое значение:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Получает или задает обычный текст части. Чтение/запись String.

Value: Текст.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getField() {#getField--}
```
public abstract IField getField()
```

Возвращает поле этой части. Только для чтения [IField](../../com.aspose.slides/ifield).

**Возвращаемое значение:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```

Преобразует эту часть в автоматически обновляемое поле.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | Тип поля [IFieldType](../../com.aspose.slides/ifieldtype) |
### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```

Преобразует эту часть в автоматически обновляемое поле.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| internalString | java.lang.String | Внутреннее имя FieldTypeEx String |
### removeField() {#removeField--}
```
public abstract void removeField()
```

Преобразует эту часть поля в простую часть.
### getRect() {#getRect--}
```
public abstract RectF getRect()
```

Получает координаты прямоугольника, ограничивающего часть. Прямоугольник включает все строки текста в части, включая пустые.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try
>  {
>  	ISlide slide = pres.getSlides().get_Item(0);
>  	IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 200, 50);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().clear();
>  	Portion portion0 = new Portion("Some text");
>  	Portion portion1 = new Portion("GetRect text");
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion0);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion1);
>  	android.graphics.RectF rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
android.graphics.RectF - Прямоугольник, ограничивающий часть android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public abstract PointF getCoordinates()
```

Получает координаты начала части. Координата X точки представляет начало части с первого символа, включая левый отступ. Координата Y включает верхний отступ.

**Возвращаемое значение:**
android.graphics.PointF - Координаты начала части android.graphics.PointF