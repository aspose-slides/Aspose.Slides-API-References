---
title: Portion
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет часть текста внутри абзаца.
type: docs
url: /ru/com.aspose.slides/portion/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

Представляет часть текста внутри абзаца текста.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Portion()](#Portion--) | Инициализирует новый экземпляр класса Portion. |
| [Portion(String str)](#Portion-java.lang.String-) | Инициализирует новый экземпляр класса Portion. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Инициализирует новый экземпляр класса Portion. |
## Методы

| Метод | Описание |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Возвращает объект форматирования, который содержит явно заданные свойства форматирования части текста без наследования. |
| [getText()](#getText--) | Получает или задает простой текст части. |
| [setText(String value)](#setText-java.lang.String-) | Получает или задает простой текст части. |
| [getField()](#getField--) | Возвращает поле этой части. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Преобразует эту часть в автоматически обновляемое поле. |
| [addField(String internalString)](#addField-java.lang.String-) | Преобразует эту часть в автоматически обновляемое поле. |
| [removeField()](#removeField--) | Преобразует эту часть поля в простую часть. |
| [getRect()](#getRect--) | Получает координаты прямоугольника, ограничивающего часть. |
| [getCoordinates()](#getCoordinates--) | Получает координаты начала части. |
| [getSlide()](#getSlide--) | Возвращает родительский слайд текста. |
| [getPresentation()](#getPresentation--) | Возвращает родительскую презентацию текста. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### Portion() {#Portion--}
```
public Portion()
```

Инициализирует новый экземпляр класса Portion.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```

Инициализирует новый экземпляр класса Portion.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```

Инициализирует новый экземпляр класса Portion.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```

Возвращает объект форматирования, который содержит явно заданные свойства форматирования части текста без наследования. Только для чтения [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Объект форматирования содержит параметры, определённые только для текущей части; унаследованные данные не применяются.

Для получения эффективных значений, включая унаследованные, используйте метод [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective).

**Возвращаемое значение:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```

Получает или задает простой текст части. Чтение/запись String.

Значение: Текст.

**Возвращаемое значение:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Получает или задает простой текст части. Чтение/запись String.

Значение: Текст.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```

Возвращает поле этой части. Только для чтения [IField](../../com.aspose.slides/ifield).

**Возвращаемое значение:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```

Преобразует эту часть в автоматически обновляемое поле.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```

Преобразует эту часть в автоматически обновляемое поле.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| internalString | java.lang.String | Внутреннее имя типа поля. |

### removeField() {#removeField--}
```
public final void removeField()
```

Преобразует эту часть поля в простую часть.

### getRect() {#getRect--}
```
public final RectF getRect()
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
android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public final PointF getCoordinates()
```

Получает координаты начала части. Координата X точки представляет начало части с первого символа, включая левый отступ. Координата Y включает верхний отступ.

**Возвращаемое значение:**
android.graphics.PointF
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Возвращает родительский слайд текста. Только для чтения [BaseSlide](../../com.aspose.slides/baseslide).

**Возвращаемое значение:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Возвращает родительскую презентацию текста. Только для чтения [IPresentation](../../com.aspose.slides/ipresentation).

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращаемое значение:**
com.aspose.slides.IDOMObject