---
title: AutoShape
second_title: Aspose.Slides for Java API Reference
description: Represents an AutoShape.
type: docs
weight: 26
url: /com.aspose.slides/autoshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**All Implemented Interfaces:**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public class AutoShape extends GeometryShape implements IAutoShape
```

Represents an AutoShape.
## Methods

| Method | Description |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Returns shape's locks. |
| [getAutoShapeLock()](#getAutoShapeLock--) | Returns autoshape's locks. |
| [getTextFrame()](#getTextFrame--) | Returns TextFrame object for the AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Adds a new TextFrame to a shape. |
| [isTextBox()](#isTextBox--) | Specifies if the shape is a text box. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```


Returns shape's locks. Read-only [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Returns:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```


Returns autoshape's locks. Read-only [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Returns:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


Returns TextFrame object for the AutoShape. Read-only [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```


Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. Read/write boolean.

**Returns:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```


Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public ITextFrame addTextFrame(String text)
```


Adds a new TextFrame to a shape. If shape already has TextFrame then simply changes its text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Default text for a new TextFrame. |

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```


Specifies if the shape is a text box.

--------------------

If shape is not specified to be a text box does not mean that it cannot have text attached to it. A text box is merely a specialized shape with specific properties.

**Returns:**
boolean
