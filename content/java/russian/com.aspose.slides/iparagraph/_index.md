---
title: IParagraph
second_title: Aspose.Slides для Java: справочник API
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
| [getParagraphFormat()](#getParagraphFormat--) | Возвращает объект форматирования для данного абзаца. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Объединяет участки с одинаковым форматированием. |
| [getText()](#getText--) | Получает или задает простой текст абзаца. |
| [setText(String value)](#setText-java.lang.String-) | Получает или задает простой текст абзаца. |
| [getRect()](#getRect--) | Получает координаты прямоугольника, ограничивающего абзац. |
| [getLinesCount()](#getLinesCount--) | Получает количество строк в абзаце. |
| [getImage()](#getImage--) | Возвращает изображение абзаца. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Возвращает изображение абзаца с указанным масштабом. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Указывает свойства фрагмента, которые будут использоваться, если после последнего будет вставлен другой фрагмент. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Указывает свойства фрагмента, которые будут использоваться, если после последнего будет вставлен другой фрагмент. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

Возвращает коллекцию текстовых фрагментов. **Только для чтения** [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Возвращаемое значение:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

Возвращает объект форматирования для данного абзаца. **Только для чтения** [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Возвращаемое значение:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Объединяет участки с одинаковым форматированием.

### getText() {#getText--}
```
public abstract String getText()
```

Получает или задает простой текст абзаца. **Чтение/запись** String.

Значение: Текст.

**Возвращаемое значение:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Получает или задает простой текст абзаца. **Чтение/запись** String.

Значение: Текст.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```

Получает координаты прямоугольника, ограничивающего абзац. Прямоугольник включает все строки текста в абзаце, включая пустые.

**Возвращаемое значение:**
java.awt.geom.Rectangle2D.Float - Прямоугольник, ограничивающий абзац java.awt.geom.Rectangle2D.Float
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


**Возвращаемое значение:**
int - количество строк в абзаце
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Возвращает изображение абзаца.

--------------------

> ```
> The following example shows how to render a paragraph as an image:
>   
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(
>          ShapeType.Rectangle, 50, 50, 150, 50);
>      IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>      paragraph.setText("Aspose Paragraph GetImage() Example");
>      IImage paragraphImage = paragraph.getImage();
>      try {
>          paragraphImage.save("paragraph.png");
>      } finally {
>          if (paragraphImage != null) paragraphImage.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
[IImage](../../com.aspose.slides/iimage) - Изображение, содержащее отрисованный абзац, или null, если абзац не найден в родительской коллекции, не имеет допустимых границ отрисовки или произошла ошибка при рендеринге изображения.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

Возвращает изображение абзаца с указанным масштабом.

--------------------

> ```
> The following example shows how to render each text box paragraph on a slide as an image with custom scaling:
>   
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      int shapeIndex = 0;
>      for (IShape shape : slide.getShapes())
>      {
>          shapeIndex++;
>          if (shape instanceof IAutoShape) {
>              IAutoShape autoShape = (IAutoShape)shape;
>              int paragraphIndex = 0;
>              for (IParagraph paragraph : autoShape.getTextFrame().getParagraphs())
>              {
>                  paragraphIndex++;
>                  IImage paragraphImage = paragraph.getImage(2f, 2f);
>                  try {
>                      if (paragraphImage != null)
>                          paragraphImage.save("shape"+shapeIndex+"_paragraph"+paragraphIndex+".png");
> 
>                  } finally {
>                      if (paragraphImage != null) paragraphImage.dispose();
>                  }
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scaleX | float | Горизонтальный коэффициент масштабирования, применяемый к изображению абзаца. |
| scaleY | float | Вертикальный коэффициент масштабирования, применяемый к изображению абзаца. |

**Возвращаемое значение:**
[IImage](../../com.aspose.slides/iimage) - Изображение, содержащее отрисованный абзац, или null, если абзац не найден в родительской коллекции, не имеет допустимых границ отрисовки или произошла ошибка при рендеринге изображения.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```

Указывает свойства фрагмента, которые будут использоваться, если после последнего будет вставлен другой фрагмент.

**Возвращаемое значение:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```

Указывает свойства фрагмента, которые будут использоваться, если после последнего будет вставлен другой фрагмент.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |