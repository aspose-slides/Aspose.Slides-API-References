---
title: IParagraph
second_title: Aspose.Slides for Java API Reference
description: Represents a paragraph of a text.
type: docs
url: /com.aspose.slides/iparagraph/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Represents a paragraph of a text.
## Methods

| Method | Description |
| --- | --- |
| [getPortions()](#getPortions--) | Returns the collection of a text portions. |
| [getParagraphFormat()](#getParagraphFormat--) | Returns the formatting object for this paragraph. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Joins runs with same formatting. |
| [getText()](#getText--) | Gets or sets the the plain text of a paragraph. |
| [setText(String value)](#setText-java.lang.String-) | Gets or sets the the plain text of a paragraph. |
| [getRect()](#getRect--) | Get coordinates of rect that bounds paragraph. |
| [getLinesCount()](#getLinesCount--) | Get number of lines in a paragraph. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Specifies the portion properties that are to be used if another portion is inserted after the last one. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Specifies the portion properties that are to be used if another portion is inserted after the last one. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```


Returns the collection of a text portions. Read-only [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Returns:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```


Returns the formatting object for this paragraph. Read-only [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Returns:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Joins runs with same formatting.

### getText() {#getText--}
```
public abstract String getText()
```


Gets or sets the the plain text of a paragraph. Read/write String.

Value: The text.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Gets or sets the the plain text of a paragraph. Read/write String.

Value: The text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```


Get coordinates of rect that bounds paragraph. The rect includes all the lines of text in paragraph, including empty ones.

**Returns:**
java.awt.geom.Rectangle2D.Float - Rectangle that bounds paragraph java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
```


Get number of lines in a paragraph.

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

**Returns:**
int - Lines count in a paragraph
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```


Specifies the portion properties that are to be used if another portion is inserted after the last one.

**Returns:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```


Specifies the portion properties that are to be used if another portion is inserted after the last one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

