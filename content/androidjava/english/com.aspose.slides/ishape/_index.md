---
title: IShape
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a shape on a slide.
type: docs
url: /com.aspose.slides/ishape/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

Represents a shape on a slide.
## Methods

| Method | Description |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Determines whether the shape is TextHolder. |
| [getPlaceholder()](#getPlaceholder--) | Returns the placeholder for a shape. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [removePlaceholder()](#removePlaceholder--) | Defines that this shape isn't a placeholder. |
| [getCustomData()](#getCustomData--) | Returns the shape's custom data. |
| [getRawFrame()](#getRawFrame--) | Returns or sets the raw shape frame's properties. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Returns or sets the raw shape frame's properties. |
| [getFrame()](#getFrame--) | Returns or sets the shape frame's properties. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Returns or sets the shape frame's properties. |
| [getLineFormat()](#getLineFormat--) | Returns the LineFormat object that contains line formatting properties for a shape. |
| [getThreeDFormat()](#getThreeDFormat--) | Returns the ThreeDFormat object that contains line formatting properties for a shape. |
| [getEffectFormat()](#getEffectFormat--) | Returns the EffectFormat object which contains pixel effects applied to a shape. |
| [getFillFormat()](#getFillFormat--) | Returns the FillFormat object that contains fill formatting properties for a shape. |
| [getImage()](#getImage--) | Returns shape thumbnail. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Returns shape thumbnail. |
| [getHidden()](#getHidden--) | Determines whether the shape is hidden. |
| [setHidden(boolean value)](#setHidden-boolean-) | Determines whether the shape is hidden. |
| [getZOrderPosition()](#getZOrderPosition--) | Returns the position of a shape in the z-order. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Returns the number of connection sites on the shape. |
| [getRotation()](#getRotation--) | Returns or sets the number of degrees the specified shape is rotated around the z-axis. |
| [setRotation(float value)](#setRotation-float-) | Returns or sets the number of degrees the specified shape is rotated around the z-axis. |
| [getX()](#getX--) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points. |
| [setX(float value)](#setX-float-) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points. |
| [getY()](#getY--) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points. |
| [setY(float value)](#setY-float-) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points. |
| [getWidth()](#getWidth--) | Gets or sets the width of the shape, measured in points. |
| [setWidth(float value)](#setWidth-float-) | Gets or sets the width of the shape, measured in points. |
| [getHeight()](#getHeight--) | Gets or sets the height of the shape, measured in points. |
| [setHeight(float value)](#setHeight-float-) | Gets or sets the height of the shape, measured in points. |
| [getAlternativeText()](#getAlternativeText--) | Returns or sets the alternative text associated with a shape. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Returns or sets the alternative text associated with a shape. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Returns or sets the title of alternative text associated with a shape. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Returns or sets the title of alternative text associated with a shape. |
| [getName()](#getName--) | Returns or sets the name of a shape. |
| [setName(String value)](#setName-java.lang.String-) | Returns or sets the name of a shape. |
| [isDecorative()](#isDecorative--) | Gets or sets 'Mark as decorative' option Reed/write boolean. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Gets or sets 'Mark as decorative' option Reed/write boolean. |
| [getShapeLock()](#getShapeLock--) | Returns shape's locks. |
| [getUniqueId()](#getUniqueId--) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and lets PowerPoint or interop code reliably reference the shape from anywhere in the document. |
| [isGrouped()](#isGrouped--) | Determines whether the shape is grouped. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Property specifies how a shape will render in black-and-white display mode.. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Property specifies how a shape will render in black-and-white display mode.. |
| [getParentGroup()](#getParentGroup--) | Returns parent GroupShape object if shape is grouped. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Saves content of Shape as SVG file. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Saves content of Shape as SVG file. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from). |
### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```


Determines whether the shape is TextHolder. Read-only boolean.

**Returns:**
boolean
### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```


Returns the placeholder for a shape. Read-only [IPlaceholder](../../com.aspose.slides/iplaceholder).

**Returns:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)
### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```


Adds a new placeholder if there is no and sets placeholder properties to a specified one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder to copy content from. |

**Returns:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - New [IPlaceholder](../../com.aspose.slides/iplaceholder).
### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```


Defines that this shape isn't a placeholder.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```


Returns the shape's custom data. Read-only [ICustomData](../../com.aspose.slides/icustomdata).

**Returns:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```


Returns or sets the raw shape frame's properties. Read/write [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
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
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // now shape inherits x, y, height, flipH, flipV values form placeholder and overrides width=100 and rotationAngle=0.
> ```

**Returns:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```


Returns or sets the raw shape frame's properties. Read/write [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
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
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // now shape inherits x, y, height, flipH, flipV values form placeholder and overrides width=100 and rotationAngle=0.
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```


Returns or sets the shape frame's properties. Read/write [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties.

**Returns:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
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
public abstract ILineFormat getLineFormat()
```


Returns the LineFormat object that contains line formatting properties for a shape. Read-only [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```


Returns the ThreeDFormat object that contains line formatting properties for a shape. Read-only [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Returns:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```


Returns the EffectFormat object which contains pixel effects applied to a shape. Read-only [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Returns:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Returns the FillFormat object that contains fill formatting properties for a shape. Read-only [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


Returns shape thumbnail. ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail.
### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```


Returns shape thumbnail.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bounds | int | Shape thumbnail bounds type. |
| scaleX | float | X scale |
| scaleY | float | Y scale |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail or null in case when ShapeThumbnailBounds.Appearance is used and a shape doesn't have visible elements.
### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```


Determines whether the shape is hidden. Read/write boolean.

**Returns:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```


Determines whether the shape is hidden. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```


Returns the position of a shape in the z-order. Shapes[0] returns the shape at the back of the z-order, and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order. Read-only int.

**Returns:**
int
### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```


Returns the number of connection sites on the shape. Read-only int.

**Returns:**
int
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```


Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write float.

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Returns:**
float
### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```


Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write float.

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```


Gets or sets the x-coordinate of the shape's upper-left corner, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Returns:**
float
### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```


Gets or sets the x-coordinate of the shape's upper-left corner, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```


Gets or sets the y-coordinate of the shape's upper-left corner, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Returns:**
float
### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```


Gets or sets the y-coordinate of the shape's upper-left corner, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```


Gets or sets the width of the shape, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```


Gets or sets the width of the shape, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Gets or sets the height of the shape, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Returns:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```


Gets or sets the height of the shape, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```


Returns or sets the alternative text associated with a shape. Read/write String.

**Returns:**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```


Returns or sets the alternative text associated with a shape. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```


Returns or sets the title of alternative text associated with a shape. Read/write String.

**Returns:**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```


Returns or sets the title of alternative text associated with a shape. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```


Returns or sets the name of a shape. Read/write String.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Returns or sets the name of a shape. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```


Gets or sets 'Mark as decorative' option Reed/write boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
boolean
### setDecorative(boolean value) {#setDecorative-boolean-}
```
public abstract void setDecorative(boolean value)
```


Gets or sets 'Mark as decorative' option Reed/write boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public abstract IBaseShapeLock getShapeLock()
```


Returns shape's locks. Read-only [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Returns:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```


Returns an internal, presentation-scoped identifier intended for use by add-ins or other code. Because this value can be reassigned by the user or programmatically, it must not be treated as a persistent unique key. Read-only long. See also \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Returns:**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```


Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and lets PowerPoint or interop code reliably reference the shape from anywhere in the document. Read-only long. See also \#getUniqueId.getUniqueId.

**Returns:**
long
### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```


Determines whether the shape is grouped. Read-only boolean.

--------------------

Property \#getParentGroup.getParentGroup returns parent GroupShape object if shape is grouped.

**Returns:**
boolean
### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```


Property specifies how a shape will render in black-and-white display mode.. Read/write [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Returns:**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```


Property specifies how a shape will render in black-and-white display mode.. Read/write [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```


Returns parent GroupShape object if shape is grouped. Otherwise returns null. Read-only [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Property \#isGrouped.isGrouped determines whether the shape is grouped.

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```


Saves content of Shape as SVG file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```


Saves content of Shape as SVG file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG generation options |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```


Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).

--------------------

> ```
> // get all (master/layout/slide) animated effects of the placeholder shape
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape = slide.getShapes().get_Item(0);
>      IEffect[] shapeEffects = slide.getTimeline().getMainSequence().getEffectsByShape(shape);
>      IShape layoutShape = shape.getBasePlaceholder();
>      IEffect[] layoutShapeEffects = slide.getLayoutSlide().getTimeline().getMainSequence().getEffectsByShape(layoutShape);
>      IShape masterShape = layoutShape.getBasePlaceholder();
>      IEffect[] masterShapeEffects = slide.getLayoutSlide().getMasterSlide().getTimeline().getMainSequence().getEffectsByShape(masterShape);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

A null is returned if the current shape is not inherited.

**Returns:**
[IShape](../../com.aspose.slides/ishape)
