---
title: Paragraph
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents a paragraph of text.
type: docs
weight: 397
url: /java/com.aspose.slides/paragraph/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IObservable, com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IObservable, IDOMObject
```

Represents a paragraph of text.
## Constructors

| Constructor | Description |
| --- | --- |
| [Paragraph()](#Paragraph--) | Initializes a new instance of the Paragraph class with default properties. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Copy constructor that initializes a new instance of a Paragraph class. |
## Methods

| Method | Description |
| --- | --- |
| [getPortions()](#getPortions--) | Returns the collection of a text portions. |
| [getParagraphFormat()](#getParagraphFormat--) | Returns the formatting object for this paragraph. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Joins runs with same formatting. |
| [getText()](#getText--) | Gets or sets the the plain text of a paragraph. |
| [setText(String value)](#setText-java.lang.String-) | Gets or sets the the plain text of a paragraph. |
| [getRect()](#getRect--) | Get coordinates of rect that bounds paragraph. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Specifies the portion properties that are to be used if another portion is inserted after the last one. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Specifies the portion properties that are to be used if another portion is inserted after the last one. |
| [subscribe(IObserver observer)](#subscribe-com.aspose.slides.IObserver-) |  |
| [unsubscribe(IObserver observer)](#unsubscribe-com.aspose.slides.IObserver-) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Returns the parent slide of a paragraph. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a paragraph. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```


Initializes a new instance of the Paragraph class with default properties.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```


Copy constructor that initializes a new instance of a Paragraph class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```


Returns the collection of a text portions. Read-only [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Returns:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```


Returns the formatting object for this paragraph. Read-only [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

The formatting object contains the formatting parameters defined for the current paragraph only, inherited data is not applied.

In order to get the effective values including inherited ones use the [ParagraphFormat\#getEffective](../../com.aspose.slides/paragraphformat\#getEffective) method.

**Returns:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


Joins runs with same formatting.

### getText() {#getText--}
```
public final String getText()
```


Gets or sets the the plain text of a paragraph. Read/write String.

Value: The text.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Gets or sets the the plain text of a paragraph. Read/write String.

Value: The text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```


Get coordinates of rect that bounds paragraph. The rect includes all the lines of text in paragraph, including empty ones.

**Returns:**
java.awt.geom.Rectangle2D.Float
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```


Specifies the portion properties that are to be used if another portion is inserted after the last one.

**Returns:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```


Specifies the portion properties that are to be used if another portion is inserted after the last one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### subscribe(IObserver observer) {#subscribe-com.aspose.slides.IObserver-}
```
public final void subscribe(IObserver observer)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| observer | com.aspose.slides.IObserver |  |

### unsubscribe(IObserver observer) {#unsubscribe-com.aspose.slides.IObserver-}
```
public final void unsubscribe(IObserver observer)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| observer | com.aspose.slides.IObserver |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Returns the parent slide of a paragraph. Read-only [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Returns the parent presentation of a paragraph. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)
