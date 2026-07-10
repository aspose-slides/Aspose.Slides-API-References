---
title: IShape
second_title: Aspose.Slides for Android via Java API 参考文档
description: 表示幻灯片上的形状。
type: docs
url: /zh/com.aspose.slides/ishape/
---
**所有实现的接口：**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

表示幻灯片上的形状。

## 方法

| 方法 | 描述 |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | 确定形状是否为 TextHolder。 |
| [getPlaceholder()](#getPlaceholder--) | 返回形状的占位符。 |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | 如果不存在占位符，则添加一个新占位符，并将占位符属性设置为指定的占位符。 |
| [removePlaceholder()](#removePlaceholder--) | 定义此形状不是占位符。 |
| [getCustomData()](#getCustomData--) | 返回形状的自定义数据。 |
| [getRawFrame()](#getRawFrame--) | 返回或设置原始形状框架的属性。 |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | 返回或设置原始形状框架的属性。 |
| [getFrame()](#getFrame--) | 返回或设置形状框架的属性。 |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | 返回或设置形状框架的属性。 |
| [getLineFormat()](#getLineFormat--) | 返回包含形状线条格式属性的 LineFormat 对象。 |
| [getThreeDFormat()](#getThreeDFormat--) | 返回包含形状线条格式属性的 ThreeDFormat 对象。 |
| [getEffectFormat()](#getEffectFormat--) | 返回包含对形状应用的像素效果的 EffectFormat 对象。 |
| [getFillFormat()](#getFillFormat--) | 返回包含形状填充格式属性的 FillFormat 对象。 |
| [getImage()](#getImage--) | 返回形状缩略图。 |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | 返回形状缩略图。 |
| [getHidden()](#getHidden--) | 确定形状是否隐藏。 |
| [setHidden(boolean value)](#setHidden-boolean-) | 确定形状是否隐藏。 |
| [getZOrderPosition()](#getZOrderPosition--) | 返回形状在 Z 顺序中的位置。 |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | 返回形状上的连接点数量。 |
| [getRotation()](#getRotation--) | 返回或设置指定形状绕 Z 轴旋转的角度（度数）。 |
| [setRotation(float value)](#setRotation-float-) | 返回或设置指定形状绕 Z 轴旋转的角度（度数）。 |
| [getX()](#getX--) | 获取或设置形状左上角的 X 坐标（以点为单位）。 |
| [setX(float value)](#setX-float-) | 获取或设置形状左上角的 X 坐标（以点为单位）。 |
| [getY()](#getY--) | 获取或设置形状左上角的 Y 坐标（以点为单位）。 |
| [setY(float value)](#setY-float-) | 获取或设置形状左上角的 Y 坐标（以点为单位）。 |
| [getWidth()](#getWidth--) | 获取或设置形状的宽度（以点为单位）。 |
| [setWidth(float value)](#setWidth-float-) | 获取或设置形状的宽度（以点为单位）。 |
| [getHeight()](#getHeight--) | 获取或设置形状的高度（以点为单位）。 |
| [setHeight(float value)](#setHeight-float-) | 获取或设置形状的高度（以点为单位）。 |
| [getAlternativeText()](#getAlternativeText--) | 返回或设置与形状关联的替代文本。 |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 返回或设置与形状关联的替代文本。 |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | 返回或设置与形状关联的替代文本标题。 |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | 返回或设置与形状关联的替代文本标题。 |
| [getName()](#getName--) | 返回或设置形状的名称。 |
| [setName(String value)](#setName-java.lang.String-) | 返回或设置形状的名称。 |
| [isDecorative()](#isDecorative--) | 获取或设置 “标记为装饰性” 选项的读/写布尔值。 |
| [setDecorative(boolean value)](#setDecorative-boolean-) | 获取或设置 “标记为装饰性” 选项的读/写布尔值。 |
| [getShapeLock()](#getShapeLock--) | 返回形状的锁定属性。 |
| [getUniqueId()](#getUniqueId--) | 返回内部的、面向演示文稿范围的标识符，供加载项或其他代码使用。 |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | 返回在幻灯片范围内唯一的标识符，该标识符在形状生命周期内保持不变，使 PowerPoint 或互操作代码能够在文档的任何位置可靠地引用该形状。 |
| [isGrouped()](#isGrouped--) | 确定形状是否已分组。 |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | 属性指定形状在黑白显示模式下的渲染方式。 |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | 属性指定形状在黑白显示模式下的渲染方式。 |
| [getParentGroup()](#getParentGroup--) | 如果形状已分组，返回父 GroupShape 对象。 |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | 将形状内容保存为 SVG 文件。 |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | 将形状内容保存为 SVG 文件。 |
| [getBasePlaceholder()](#getBasePlaceholder--) | 返回基本占位符形状（当前形状继承自布局和/或母版幻灯片的形状）。 |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

确定形状是否为 TextHolder。只读布尔值。

**返回：**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

返回形状的占位符。只读 [IPlaceholder](../../com.aspose.slides/iplaceholder)。

**返回：**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

如果不存在占位符，则添加一个新占位符，并将占位符属性设置为指定的占位符。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | 复制内容的占位符。 |

**返回：**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - 新 [IPlaceholder](../../com.aspose.slides/iplaceholder)。

### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

定义此形状不是占位符。

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

返回形状的自定义数据。只读 [ICustomData](../../com.aspose.slides/icustomdata)。

**返回：**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

返回或设置原始形状框架的属性。读/写 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //或
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //此类代码可能导致不明确的情况。因此已对在 IShape.getFrame() 中使用未定义值添加了限制。x、y、width、height、flipH、flipV 和 rotationAngle 的值必须已定义（不能为 Float.NaN 或 NullableBool.NotDefined）。上述示例代码现在会抛出 ArgumentException 异常。
>  //这适用于以下用例：
>  IShape shape = ...;
>  shape.setFrame(...); // 不能为未定义
>  IShapeCollection shapes = ...;
>  // x、y、width、height 参数不能为 Float.NaN:
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
>  IShape shape = ...; // 形状链接到占位符
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // 现在形状从占位符继承 x、y、height、flipH、flipV 的值，并将 width=100 和 rotationAngle=0 覆盖进去.
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
>  //或
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //此类代码可能导致不明确的情况。因此已对在 IShape.getFrame() 中使用未定义值添加了限制。x、y、width、height、flipH、flipV 和 rotationAngle 的值必须已定义（不能为 Float.NaN 或 NullableBool.NotDefined）。上述示例代码现在会抛出 ArgumentException 异常。
>  //这适用于以下用例：
>  IShape shape = ...;
>  shape.setFrame(...); // 不能为未定义
>  IShapeCollection shapes = ...;
>  // x、y、width、height 参数不能为 Float.NaN:
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
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // 现在形状从占位符继承 x、y、height、flipH、flipV 的值，并将 width=100 和 rotationAngle=0 覆盖进去.
>  ```
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

返回或设置指定形状绕 Z 轴旋转的角度（度）。正值表示顺时针旋转；负值表示逆时针旋转。读/写 float。

--------------------

返回值始终已定义（不是 Float.NaN）。分配的值必须已定义（不是 Float.NaN）。可以为 RawFrame 实例属性设置未定义值。

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

获取或设置形状左上角的 X 坐标（以点为单位）。读/写 float。

--------------------

返回的值始终已定义，永不为 Float.NaN。分配的值也必须已定义；仅对 RawFrame 实例的属性分配 Float.NaN。

**Returns:**
float
### setX(float value) {#setX-float-}
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

获取或设置形状左上角的 Y 坐标（以点为单位）。读/写 float。

--------------------

返回的值始终已定义，永不为 Float.NaN。分配的值也必须已定义；仅对 RawFrame 实例的属性分配 Float.NaN。

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
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

将 Shape 内容保存为 SVG 文件。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | 目标流 |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 生成选项 |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()


返回基本占位符形状（当前形状继承自布局和/或母版幻灯片的形状）。

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

如果当前形状未被继承，则返回 null。

**返回：**
[IShape](../../com.aspose.slides/ishape)