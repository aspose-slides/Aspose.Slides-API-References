---
title: IParagraph
second_title: Aspose.Slides для Android через Java API справочник
description: Представляет абзац текста.
type: docs
url: /ru/com.aspose.slides/iparagraph/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Представляет абзац текста.
## Методы

| Метод | Описание |
| --- | --- |
| [getPortions()](#getPortions--) | Возвращает коллекцию текстовых фрагментов. |
| [getParagraphFormat()](#getParagraphFormat--) | Возвращает объект форматирования для этого абзаца. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Объединяет фрагменты с одинаковым форматированием. |
| [getText()](#getText--) | Получает или задает простой текст абзаца. |
| [setText(String value)](#setText-java.lang.String-) | Получает или задает простой текст абзаца. |
| [getRect()](#getRect--) | Получает координаты прямоугольника, ограничивающего абзац. |
| [getLinesCount()](#getLinesCount--) | Получает количество строк в абзаце. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Указывает свойства части, которые будут использованы, если после последней части будет вставлена новая. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Указывает свойства части, которые будут использованы, если после последней части будет вставлена новая. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```


Возвращает коллекцию текстовых фрагментов. Только для чтения [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Возвращает:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```


Возвращает объект форматирования для этого абзаца. Только для чтения [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Возвращает:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Объединяет фрагменты с одинаковым форматированием.

### getText() {#getText--}
```
public abstract String getText()
```


Получает или задает простой текст абзаца. Чтение/запись String.

Значение: Текст.

**Возвращает:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Получает или задает простой текст абзаца. Чтение/запись String.

Значение: Текст.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getRect() {#getRect--}
```
public abstract RectF getRect()
```


Получает координаты прямоугольника, ограничивающего абзац. Прямоугольник включает все строки текста в абзаце, включая пустые.

**Возвращает:**
android.graphics.RectF — Прямоугольник, ограничивающий абзац android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
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

**Возвращает:**
int - Количество строк в абзаце
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```


Указывает свойства части, которые будут использованы, если после последней части будет вставлена новая.

**Возвращает:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```


Указывает свойства части, которые будут использованы, если после последней части будет вставлена новая.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |   |