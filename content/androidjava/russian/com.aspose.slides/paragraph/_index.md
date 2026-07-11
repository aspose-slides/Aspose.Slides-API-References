---
title: Paragraph
second_title: Aspose.Slides для Android через справочник API Java
description: Представляет абзац текста.
type: docs
url: /ru/com.aspose.slides/paragraph/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

Представляет абзац текста.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Paragraph()](#Paragraph--) | Инициализирует новый экземпляр класса Paragraph с свойствами по умолчанию. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Конструктор копирования, инициализирующий новый экземпляр класса Paragraph. |
## Методы

| Метод | Описание |
| --- | --- |
| [getPortions()](#getPortions--) | Возвращает коллекцию текстовых фрагментов. |
| [getParagraphFormat()](#getParagraphFormat--) | Возвращает объект форматирования для данного абзаца. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Объединяет участки с одинаковым форматированием. |
| [getText()](#getText--) | Получает или задает простой текст абзаца. |
| [setText(String value)](#setText-java.lang.String-) | Получает или задает простой текст абзаца. |
| [getRect()](#getRect--) | Получает координаты прямоугольника, ограничивающего абзац. |
| [getLinesCount()](#getLinesCount--) | Получает количество строк в абзаце. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Указывает свойства фрагмента, которые будут использоваться, если после последнего будет вставлен другой фрагмент. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Указывает свойства фрагмента, которые будут использоваться, если после последнего будет вставлен другой фрагмент. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Возвращает родительский слайд абзаца. |
| [getPresentation()](#getPresentation--) | Возвращает родительскую презентацию абзаца. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```


Инициализирует новый экземпляр класса Paragraph с свойствами по умолчанию.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```


Конструктор копирования, инициализирующий новый экземпляр класса Paragraph.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```


Возвращает коллекцию текстовых фрагментов. Только для чтения [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Возвращаемое значение:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```


Возвращает объект форматирования для данного абзаца. Только для чтения [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

Объект форматирования содержит параметры форматирования, определённые только для текущего абзаца; унаследованные данные не применяются.

Чтобы получить эффективные значения, включая унаследованные, используйте метод [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective).

**Возвращаемое значение:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


Объединяет участки с одинаковым форматированием.

### getText() {#getText--}
```
public final String getText()
```


Получает или задает простой текст абзаца. Чтение/запись String.

Значение: Текст.

**Возвращаемое значение:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Получает или задает простой текст абзаца. Чтение/запись String.

Значение: Текст.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final RectF getRect()
```


Получает координаты прямоугольника, ограничивающего абзац. Прямоугольник включает все строки текста в абзаце, включая пустые.

**Возвращаемое значение:**
android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```


Получает количество строк в абзаце.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      IParagraph para = ashp.getTextFrame().getParagraphs().get_Item(0);
>      IPortion portion = para.getPortions().get_Item(0);
>      portion.setText("Aspose Paragraph GetLinesCount() Example");
>      System.out.println("Lines Count = " + para.getLinesCount());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
int - Количество строк в абзаце
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```


Указывает свойства фрагмента, которые будут использоваться, если после последнего будет вставлен другой фрагмент.

**Возвращаемое значение:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```


Указывает свойства фрагмента, которые будут использоваться, если после последнего будет вставлен другой фрагмент.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Возвращает объект Parent_Immediate. Только для чтения IDDOMObject.

**Возвращаемое значение:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Возвращает родительский слайд абзаца. Только для чтения [BaseSlide](../../com.aspose.slides/baseslide).

**Возвращаемое значение:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Возвращает родительскую презентацию абзаца. Только для чтения [IPresentation](../../com.aspose.slides/ipresentation).

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation)