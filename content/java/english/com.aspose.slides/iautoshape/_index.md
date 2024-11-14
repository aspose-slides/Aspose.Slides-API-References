---
title: IAutoShape
second_title: Aspose.Slides for Java API Reference
description: Represents an AutoShape.
type: docs
url: /com.aspose.slides/iautoshape/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

Represents an AutoShape.
## Methods

| Method | Description |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | Returns AutoShape's locks. |
| [getTextFrame()](#getTextFrame--) | Returns TextFrame object for the AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Adds a new TextFrame to a shape. |
| [isTextBox()](#isTextBox--) | Specifies if the shape is a text box. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```


Returns AutoShape's locks. Read-only [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Returns:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Returns TextFrame object for the AutoShape. Read-only [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```


Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. Read/write boolean.

**Returns:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```


Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```


Adds a new TextFrame to a shape. If shape already has TextFrame then simply changes its text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Default text for a new TextFrame. |

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe) - New [ITextFrame](../../com.aspose.slides/itextframe) object.
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```


Specifies if the shape is a text box.

--------------------

If shape is not specified to be a text box does not mean that it cannot have text attached to it. A text box is merely a specialized shape with specific properties.

**Returns:**
boolean
