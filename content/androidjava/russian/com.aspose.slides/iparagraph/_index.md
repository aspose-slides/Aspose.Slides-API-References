---
title: IParagraph
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет абзац текста.
type: docs
url: /ru/com.aspose.slides/iparagraph/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Представляет параграф текста.
## Методы

| Method | Description |
| --- | --- |
| [getPortions()](#getPortions--) | Возвращает коллекцию текстовых фрагментов. |
| [getParagraphFormat()](#getParagraphFormat--) | Возвращает объект форматирования для этого параграфа. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Объединяет фрагменты с одинаковым форматированием. |
| [getText()](#getText--) | Получает или задает простой текст параграфа. |
| [setText(String value)](#setText-java.lang.String-) | Получает или задает простой текст параграфа. |
| [getRect()](#getRect--) | Получает координаты прямоугольника, ограничивающего параграф. |
| [getLinesCount()](#getLinesCount--) | Получает количество строк в параграфе. |
| [getImage()](#getImage--) | Возвращает изображение параграфа. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Возвращает изображение параграфа с указанным масштабом. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Указывает свойства фрагмента, которые будут использоваться при вставке другого фрагмента после последнего. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Указывает свойства фрагмента, которые будут использоваться при вставке другого фрагмента после последнего. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

Возвращает коллекцию текстовых фрагментов. Только для чтения [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Возвращаемое значение:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

Возвращает объект форматирования для этого параграфа. Только для чтения [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Возвращаемое значение:**
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

Получает или задает простой текст параграфа. Чтение/запись String.

Value: Текст.

**Возвращаемое значение:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Получает или задает простой текст параграфа. Чтение/запись String.

Value: Текст.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getRect() {#getRect--}
```
public abstract RectF getRect()
```

Получает координаты прямоугольника, ограничивающего параграф. Прямоугольник включает все строки текста в параграфе, включая пустые.

**Возвращаемое значение:**
android.graphics.RectF - Rectangle that bounds paragraph android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
```

Получает количество строк в параграфе.

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
int - Lines count in a paragraph
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Возвращает изображение параграфа.

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
[IImage](../../com.aspose.slides/iimage) - An image containing the rendered paragraph, or null if the paragraph cannot be found in its parent collection, has no valid rendering bounds, or an error occurs while rendering the image.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

Возвращает изображение параграфа с указанным масштабом.

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
| Parameter | Type | Description |
| --- | --- | --- |
| scaleX | float | Горизонтальный коэффициент масштабирования, применяемый к изображению параграфа. |
| scaleY | float | Вертикальный коэффициент масштабирования, применяемый к изображению параграфа. |

**Возвращаемое значение:**
[IImage](../../com.aspose.slides/iimage) - An image containing the rendered paragraph, or null if the paragraph cannot be found in its parent collection, has no valid rendering bounds, or an error occurs while rendering the image.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```

Указывает свойства фрагмента, которые будут использоваться при вставке другого фрагмента после последнего.

**Возвращаемое значение:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```

Указывает свойства фрагмента, которые будут использоваться при вставке другого фрагмента после последнего.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |