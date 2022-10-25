---
title: Shape
second_title: Aspose.Slides for Java API Reference
description: Represents a shape on a slide.
type: docs
weight: 484
url: /java/com.aspose.slides/shape/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject
```
public class Shape implements IShape, IDOMObject
```

Represents a shape on a slide.
## Methods

| Method | Description |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Determines whether the shape is TextHolder\_PPT. |
| [getPlaceholder()](#getPlaceholder--) | Returns the placeholder for a shape. |
| [removePlaceholder()](#removePlaceholder--) | Defines that this shape isn't a placeholder. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [getCustomData()](#getCustomData--) | Returns the shape's custom data. |
| [getRawFrame()](#getRawFrame--) | Returns or sets the raw shape frame's properties. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Returns or sets the raw shape frame's properties. |
| [getFrame()](#getFrame--) | Returns or sets the shape frame's properties. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Returns or sets the shape frame's properties. |
| [getLineFormat()](#getLineFormat--) | Returns the LineFormat object that contains line formatting properties for a shape. |
| [getThreeDFormat()](#getThreeDFormat--) | Returns the ThreeDFormat object that 3d effect properties for a shape. |
| [getEffectFormat()](#getEffectFormat--) | Returns the EffectFormat object which contains pixel effects applied to a shape. |
| [getFillFormat()](#getFillFormat--) | Returns the FillFormat object that contains fill formatting properties for a shape. |
| [getThumbnail()](#getThumbnail--) | Returns shape thumbnail. |
| [getThumbnail(int bounds, float scaleX, float scaleY)](#getThumbnail-int-float-float-) | Returns shape thumbnail. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Saves content of Shape as SVG file. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Saves content of Shape as SVG file. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Returns or sets the hyperlink defined for mouse click. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Returns or sets the hyperlink defined for mouse click. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Returns or sets the hyperlink defined for mouse over. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Returns or sets the hyperlink defined for mouse over. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Returns the hyperlink manager. |
| [getHidden()](#getHidden--) | Determines whether the shape is hidden. |
| [setHidden(boolean value)](#setHidden-boolean-) | Determines whether the shape is hidden. |
| [getZOrderPosition()](#getZOrderPosition--) | Returns the position of a shape in the z-order. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Returns the number of connection sites on the shape. |
| [getRotation()](#getRotation--) | Returns or sets the number of degrees the specified shape is rotated around the z-axis. |
| [setRotation(float value)](#setRotation-float-) | Returns or sets the number of degrees the specified shape is rotated around the z-axis. |
| [getX()](#getX--) | Returns or sets the x-coordinate of the upper-left corner of the shape. |
| [setX(float value)](#setX-float-) | Returns or sets the x-coordinate of the upper-left corner of the shape. |
| [getY()](#getY--) | Returns or sets the y-coordinate of the upper-left corner of the shape. |
| [setY(float value)](#setY-float-) | Returns or sets the y-coordinate of the upper-left corner of the shape. |
| [getWidth()](#getWidth--) | Returns or sets the width of the shape. |
| [setWidth(float value)](#setWidth-float-) | Returns or sets the width of the shape. |
| [getHeight()](#getHeight--) | Returns or sets the height of the shape. |
| [setHeight(float value)](#setHeight-float-) | Returns or sets the height of the shape. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Property specifies how a shape will render in black-and-white display mode.. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Property specifies how a shape will render in black-and-white display mode.. |
| [getUniqueId()](#getUniqueId--) | Gets unique shape identifier in presentation scope. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Gets unique shape identifier in slide scope. |
| [getAlternativeText()](#getAlternativeText--) | Returns or sets the alternative text associated with a shape. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Returns or sets the alternative text associated with a shape. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Returns or sets the title of alternative text associated with a shape. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Returns or sets the title of alternative text associated with a shape. |
| [getName()](#getName--) | Returns or sets the name of a shape. |
| [setName(String value)](#setName-java.lang.String-) | Returns or sets the name of a shape. |
| [getShapeLock()](#getShapeLock--) | Returns shape's locks. |
| [isGrouped()](#isGrouped--) | Determines whether the shape is grouped. |
| [getParentGroup()](#getParentGroup--) | Returns parent GroupShape object if shape is grouped. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Returns the parent slide of a shape. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a slide. |
### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```


Determines whether the shape is TextHolder\_PPT. Read-only  boolean .

**Returns:**
boolean
### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```


Returns the placeholder for a shape. Returns null if the shape has no placeholder. Read-only [IPlaceholder](../../com.aspose.slides/iplaceholder).

**Returns:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)
### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```


Defines that this shape isn't a placeholder.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```


Adds a new placeholder if there is no and sets placeholder properties to a specified one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder to copy content from. |

**Returns:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - New [Placeholder](../../com.aspose.slides/placeholder)(\#getPlaceholder.getPlaceholder).
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```


Returns the shape's custom data. Read-only [ICustomData](../../com.aspose.slides/icustomdata).

**Returns:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```


Returns or sets the raw shape frame's properties. Read/write [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sence in general case (particulary in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //or
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Such code can lead to unclear situations. So restrictions had been added for using undefined values for IShape.getFrame(). Values of x, y, width, height, flipH, flipV and rotationAngle must be defined (not Float.NaN or NullableBool.NotDefined). Example code above now throws ArgumentException exception.
>  //This applies to these use cases:
>  IShape shape = ...;
>  shape.setFrame(...); // cannot be undefined
>  IShapeCollection shapes = ...;
>  // x, y, width, height parameters cannot be Float.NaN:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  //But IShape.RawFrame frame properties can be undefined. This make sence when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // now shape inherits x, y, height, flipH, flipV values form placeholder and overrides width=100 and rotationAngle=0.{code}
> ```

**Returns:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```


Returns or sets the raw shape frame's properties. Read/write [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sence in general case (particulary in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //or
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Such code can lead to unclear situations. So restrictions had been added for using undefined values for IShape.getFrame(). Values of x, y, width, height, flipH, flipV and rotationAngle must be defined (not Float.NaN or NullableBool.NotDefined). Example code above now throws ArgumentException exception.
>  //This applies to these use cases:
>  IShape shape = ...;
>  shape.setFrame(...); // cannot be undefined
>  IShapeCollection shapes = ...;
>  // x, y, width, height parameters cannot be Float.NaN:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  //But IShape.RawFrame frame properties can be undefined. This make sence when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // now shape inherits x, y, height, flipH, flipV values form placeholder and overrides width=100 and rotationAngle=0.{code}
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```


Returns or sets the shape frame's properties. Read/write [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties.

**Returns:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```


Returns or sets the shape frame's properties. Read/write [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```


Returns the LineFormat object that contains line formatting properties for a shape. Note: can return null for certain types of shapes which don't have line properties. Read-only [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```


Returns the ThreeDFormat object that 3d effect properties for a shape. Note: can return null for certain types of shapes which don't have 3d properties. Read-only [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Returns:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```


Returns the EffectFormat object which contains pixel effects applied to a shape. Note: can return null for certain types of shapes which don't have effect properties. Read-only [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Returns:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```


Returns the FillFormat object that contains fill formatting properties for a shape. Note: can return null for certain types of shapes which don't have fill properties. Read-only [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getThumbnail() {#getThumbnail--}
```
public final BufferedImage getThumbnail()
```


Returns shape thumbnail. ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

**Returns:**
java.awt.image.BufferedImage - Shape thumbnail.
### getThumbnail(int bounds, float scaleX, float scaleY) {#getThumbnail-int-float-float-}
```
public final BufferedImage getThumbnail(int bounds, float scaleX, float scaleY)
```


Returns shape thumbnail.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bounds | int | Shape thumbnail bounds type. |
| scaleX | float | X scale |
| scaleY | float | Y scale |

**Returns:**
java.awt.image.BufferedImage - Shape thumbnail or null in case when ShapeThumbnailBounds.Appearance is used and a shape doesn't have visible elements.
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```


Saves content of Shape as SVG file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```


Saves content of Shape as SVG file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG generation options |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```


Returns or sets the hyperlink defined for mouse click. Read/write [IHyperlink](../../com.aspose.slides/ihyperlink).

**Returns:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```


Returns or sets the hyperlink defined for mouse click. Read/write [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```


Returns or sets the hyperlink defined for mouse over. Read/write [IHyperlink](../../com.aspose.slides/ihyperlink).

**Returns:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```


Returns or sets the hyperlink defined for mouse over. Read/write [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```


Returns the hyperlink manager. Read-only [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Returns:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)
### getHidden() {#getHidden--}
```
public final boolean getHidden()
```


Determines whether the shape is hidden. Read/write  boolean .

**Returns:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```


Determines whether the shape is hidden. Read/write  boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```


Returns the position of a shape in the z-order. Shapes[0] returns the shape at the back of the z-order, and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order. Read-only  int .

**Returns:**
int
### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```


Returns the number of connection sites on the shape. Read-only  int .

**Returns:**
int
### getRotation() {#getRotation--}
```
public final float getRotation()
```


Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write  float .

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Returns:**
float
### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```


Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write  float .

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```


Returns or sets the x-coordinate of the upper-left corner of the shape. Read/write  float .

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Returns:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


Returns or sets the x-coordinate of the upper-left corner of the shape. Read/write  float .

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```


Returns or sets the y-coordinate of the upper-left corner of the shape. Read/write  float .

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Returns:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


Returns or sets the y-coordinate of the upper-left corner of the shape. Read/write  float .

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Returns or sets the width of the shape. Read/write  float .

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Returns or sets the width of the shape. Read/write  float .

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Returns or sets the height of the shape. Read/write  float .

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Returns:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Returns or sets the height of the shape. Read/write  float .

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```


Property specifies how a shape will render in black-and-white display mode.. Read/write [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Returns:**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```


Property specifies how a shape will render in black-and-white display mode.. Read/write [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```


Gets unique shape identifier in presentation scope. Read-only long. See also (\#getOfficeInteropShapeId.getOfficeInteropShapeId) for getting unique shape identifier in slide scope.

**Returns:**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```


Gets unique shape identifier in slide scope. Read-only long. See also (\#getUniqueId.getUniqueId) for getting unique shape identifier in presentation scope.

**Returns:**
long
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Returns or sets the alternative text associated with a shape. Read/write String.

**Returns:**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Returns or sets the alternative text associated with a shape. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```


Returns or sets the title of alternative text associated with a shape. Read/write String.

**Returns:**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```


Returns or sets the title of alternative text associated with a shape. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```


Returns or sets the name of a shape. Must be not null. Use empty string value if needed. Read/write String.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Returns or sets the name of a shape. Must be not null. Use empty string value if needed. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getShapeLock() {#getShapeLock--}
```
public IBaseShapeLock getShapeLock()
```


Returns shape's locks. Read-only [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Returns:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```


Determines whether the shape is grouped. Read-only  boolean .

--------------------

Property (\#getParentGroup.getParentGroup) returns parent GroupShape object if shape is grouped.

**Returns:**
boolean
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```


Returns parent GroupShape object if shape is grouped. Otherwise returns null. Read-only [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Property (\#isGrouped.isGrouped) determines whether the shape is grouped.

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape)
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


Returns the parent slide of a shape. Read-only [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Returns the parent presentation of a slide. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)
