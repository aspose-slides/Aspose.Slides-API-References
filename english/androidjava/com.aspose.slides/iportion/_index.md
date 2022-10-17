---
title: IPortion
second_title: Aspose.Slides for Android via Java API Reference
description:  Represents a portion of text inside a text paragraph.
type: docs
weight: 968
url: /androidjava/com.aspose.slides/iportion/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

Represents a portion of text inside a text paragraph.
## Methods

| Method | Description |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Returns formatting object which contains explicitly set formatting properties of the text portion with no inheritance applied. |
| [getText()](#getText--) | Gets or sets the plain text of a portion. |
| [setText(String value)](#setText-java.lang.String-) | Gets or sets the plain text of a portion. |
| [getField()](#getField--) | Returns a field of this portion. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Converts this portion to the automaticaly updated field. |
| [addField(String internalString)](#addField-java.lang.String-) | Converts this portion to the automaticaly updated field. |
| [removeField()](#removeField--) | Converts this field portion to the simple portion. |
| [getRect()](#getRect--) | Get coordinates of rect that bounds portion. |
| [getCoordinates()](#getCoordinates--) | Get coordinates of the beginning of the portion. |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```


Returns formatting object which contains explicitly set formatting properties of the text portion with no inheritance applied. Read-only [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

The formatting object contains the formatting parameters defined for the current portion only, inherited data is not applied.

In order to get the effective values including inherited ones use [IPortionFormat\#getEffective](../../com.aspose.slides/iportionformat\#getEffective) method.

**Returns:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```


Gets or sets the plain text of a portion. Read/write String.

Value: The text.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Gets or sets the plain text of a portion. Read/write String.

Value: The text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public abstract IField getField()
```


Returns a field of this portion. Read-only [IField](../../com.aspose.slides/ifield).

**Returns:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```


Converts this portion to the automaticaly updated field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | Type of field [IFieldType](../../com.aspose.slides/ifieldtype) |

### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```


Converts this portion to the automaticaly updated field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| internalString | java.lang.String | Internal name of FieldTypeEx String |

### removeField() {#removeField--}
```
public abstract void removeField()
```


Converts this field portion to the simple portion.

### getRect() {#getRect--}
```
public abstract RectF getRect()
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
android.graphics.RectF - Rectangle that bounds portion android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public abstract PointF getCoordinates()
```


Get coordinates of the beginning of the portion. The X coordinate of point represents the portion beginning from the first character including left side bearing. The Y coordinate includes top side bearing.

**Returns:**
android.graphics.PointF - Coordinates of the beginning of the portion android.graphics.PointF
