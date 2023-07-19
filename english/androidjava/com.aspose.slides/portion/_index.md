---
title: Portion
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a portion of text inside a text paragraph.
type: docs
weight: 433
url: /androidjava/com.aspose.slides/portion/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

Represents a portion of text inside a text paragraph.
## Constructors

| Constructor | Description |
| --- | --- |
| [Portion()](#Portion--) | Initializes a new instance of the Portion class. |
| [Portion(String str)](#Portion-java.lang.String-) | Initializes a new instance of the Portion class. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Initializes a new instance of the Portion class. |
## Methods

| Method | Description |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Returns oformatting bject which contains explicitly set formatting properties of the text portion with no inheritance applied. |
| [getText()](#getText--) | Gets or sets the plain text of a portion. |
| [setText(String value)](#setText-java.lang.String-) | Gets or sets the plain text of a portion. |
| [getField()](#getField--) | Returns a field of this portion. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Converts this portion to the automaticaly updated field. |
| [addField(String internalString)](#addField-java.lang.String-) | Converts this portion to the automaticaly updated field. |
| [removeField()](#removeField--) | Converts this field portion to the simple portion. |
| [getRect()](#getRect--) | Get coordinates of rect that bounds portion. |
| [getCoordinates()](#getCoordinates--) | Get coordinates of the beginning of the portion. |
| [getSlide()](#getSlide--) | Returns the parent slide of a text. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a text. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Portion() {#Portion--}
```
public Portion()
```


Initializes a new instance of the Portion class.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```


Initializes a new instance of the Portion class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```


Initializes a new instance of the Portion class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```


Returns oformatting bject which contains explicitly set formatting properties of the text portion with no inheritance applied. Read-only [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

The formatting object contains the formatting parameters defined for the current portion only, inherited data is not applied.

In order to get the effective values including inherited ones use the [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective) method.

**Returns:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```


Gets or sets the plain text of a portion. Read/write String.

Value: The text.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Gets or sets the plain text of a portion. Read/write String.

Value: The text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```


Returns a field of this portion. Read-only [IField](../../com.aspose.slides/ifield).

**Returns:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```


Converts this portion to the automaticaly updated field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```


Converts this portion to the automaticaly updated field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| internalString | java.lang.String | Internal name of FieldType. |

### removeField() {#removeField--}
```
public final void removeField()
```


Converts this field portion to the simple portion.

### getRect() {#getRect--}
```
public final RectF getRect()
```


Get coordinates of rect that bounds portion. The rect includes all the lines of text in portion, including empty ones.

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

**Returns:**
android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public final PointF getCoordinates()
```


Get coordinates of the beginning of the portion. The X coordinate of point represents the portion beginning from the first character including left side bearing. The Y coordinate includes top side bearing.

**Returns:**
android.graphics.PointF
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Returns the parent slide of a text. Read-only [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Returns the parent presentation of a text. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
