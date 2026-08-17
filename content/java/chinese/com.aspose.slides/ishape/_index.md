---
title: IShape
second_title: Aspose.Slides for Java API 参考
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
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | 如果不存在，则添加一个新占位符并将占位符属性设置为指定的占位符。 |
| [removePlaceholder()](#removePlaceholder--) | 定义此形状不是占位符。 |
| [getCustomData()](#getCustomData--) | 返回形状的自定义数据。 |
| [getRawFrame()](#getRawFrame--) | 返回或设置原始形状框架的属性。 |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | 返回或设置原始形状框架的属性。 |
| [getFrame()](#getFrame--) | 返回或设置形状框架的属性。 |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | 返回或设置形状框架的属性。 |
| [getLineFormat()](#getLineFormat--) | 返回包含形状线条格式属性的 LineFormat 对象。 |
| [getThreeDFormat()](#getThreeDFormat--) | 返回包含形状线条格式属性的 ThreeDFormat 对象。 |
| [getEffectFormat()](#getEffectFormat--) | 返回包含应用于形状的像素效果的 EffectFormat 对象。 |
| [getFillFormat()](#getFillFormat--) | 返回包含形状填充格式属性的 FillFormat 对象。 |
| [getImage()](#getImage--) | 返回形状缩略图。 |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | 返回形状缩略图。 |
| [getHidden()](#getHidden--) | 确定形状是否隐藏。 |
| [setHidden(boolean value)](#setHidden-boolean-) | 确定形状是否隐藏。 |
| [getZOrderPosition()](#getZOrderPosition--) | 返回形状在 Z 顺序中的位置。 |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | 返回形状的连接点数量。 |
| [getRotation()](#getRotation--) | 返回或设置指定形状绕 Z 轴旋转的角度（度）。 |
| [setRotation(float value)](#setRotation-float-) | 返回或设置指定形状绕 Z 轴旋转的角度（度）。 |
| [getX()](#getX--) | 获取或设置形状左上角的 X 坐标（以点为单位）。 |
| [setX(float value)](#setX-float-) | 获取或设置形状左上角的 X 坐标（以点为单位）。 |
| [getY()](#getY--) | 获取或设置形状左上角的 Y 坐标（以点为单位）。 |
| [setY(float value)](#setY-float-) | 获取或设置形状左上角的 Y 坐标（以点为单位）。 |
| [getWidth()](#getWidth--) | 获取或设置形状的宽度（以点为单位）。 |
| [setWidth(float value)](#setWidth-float-) | 获取或设置形状的宽度（以点为单位）。 |
| [getHeight()](#getHeight--) | 获取或设置形状的高度（以点为单位）。 |
| [setHeight(float value)](#setHeight-float-) | 获取或设置形状的高度（以点为单位）。 |
| [getAlternativeText()](#getAlternativeText--) | 返回或设置与形状关联的备用文本。 |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 返回或设置与形状关联的备用文本。 |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | 返回或设置与形状关联的备用文本标题。 |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | 返回或设置与形状关联的备用文本标题。 |
| [getName()](#getName--) | 返回或设置形状的名称。 |
| [setName(String value)](#setName-java.lang.String-) | 返回或设置形状的名称。 |
| [isDecorative()](#isDecorative--) | 获取或设置“标记为装饰性”选项的可读写 boolean。 |
| [setDecorative(boolean value)](#setDecorative-boolean-) | 获取或设置“标记为装饰性”选项的可读写 boolean。 |
| [getShapeLock()](#getShapeLock--) | 返回形状的锁定状态。 |
| [getUniqueId()](#getUniqueId--) | 返回内部的、面向演示文稿的标识符，供插件或其他代码使用。 |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | 返回在幻灯片范围内唯一的标识符，在形状的整个生命周期内保持不变，使 PowerPoint 或互操作代码能够从文档的任意位置可靠地引用该形状。 |
| [isGrouped()](#isGrouped--) | 确定形状是否被分组。 |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | 属性指定形状在黑白显示模式下的渲染方式。 |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | 属性指定形状在黑白显示模式下的渲染方式。 |
| [getParentGroup()](#getParentGroup--) | 如果形状被分组，则返回父 GroupShape 对象。 |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | 将 Shape 内容保存为 SVG 文件。 |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | 将 Shape 内容保存为 SVG 文件。 |
| [getBasePlaceholder()](#getBasePlaceholder--) | 返回基本占位符形状（来自布局和/或母版幻灯片的形状，当前形状从中继承）。 |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

确定形状是否为 TextHolder。只读 boolean。

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

如果不存在，则添加一个新占位符并将占位符属性设置为指定的占位符。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | 要从中复制内容的占位符。 |

**返回：**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - New [IPlaceholder](../../com.aspose.slides/iplaceholder)。

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

返回或设置原始形状框架的属性。可读写 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

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

**返回：**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

返回或设置原始形状框架的属性。可读写 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

> ```
> 尝试将未定义的帧分配给 IShape.getFrame() 的代码在一般情况下没有意义（特别是当父 GroupShape 多层嵌套在其他 GroupShape 中时）。例如：
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //或
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //此类代码可能导致不明确的情况。因此已添加对在 IShape.getFrame() 中使用未定义值的限制。x、y、width、height、flipH、flipV 和 rotationAngle 的值必须已定义（不能为 Float.NaN 或 NullableBool.NotDefined）。上述示例代码现在会抛出 ArgumentException 异常。
>  //这适用于以下使用情况：
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
>  但是 IShape.RawFrame 的帧属性可以是未定义的。这在形状链接到占位符时是有意义的。此时未定义的形状帧值会被父占位符形状覆盖。如果该形状没有父占位符形状，则在基于其 IShape.RawFrame 评估有效帧时，该形状使用默认值。默认值为 x、y、width、height、flipH、flipV 和 rotationAngle 的 0 和 NullableBool.False。例如：
>  IShape shape = ...; // 形状已链接到占位符
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // 现在形状从占位符继承 x、y、height、flipH、flipV 的值，并覆盖 width=100 和 rotationAngle=0.
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

返回或设置形状框架的属性。可读写 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

返回的 IShapeFrame 实例的每个属性的值均未定义（不是 NaN 或 NotDefined）。分配的 IShapeFrame 实例的每个属性的值必须未定义（不能是 NaN 或 NotDefined）。可以为 RawFrame 实例属性设置未定义的值。

**返回：**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

返回或设置形状框架的属性。可读写 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

返回的 IShapeFrame 实例的每个属性的值均未定义（不是 NaN 或 NotDefined）。分配的 IShapeFrame 实例的每个属性的值必须未定义（不能是 NaN 或 NotDefined）。可以为 RawFrame 实例属性设置未定义的值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

返回包含形状线条格式属性的 LineFormat 对象。只读 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回：**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

返回包含形状线条格式属性的 ThreeDFormat 对象。只读 [IThreeDFormat](../../com.aspose.slides/ithreedformat)。

**返回：**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

返回包含应用于形状的像素效果的 EffectFormat 对象。只读 [IEffectFormat](../../com.aspose.slides/ieffectformat)。

**返回：**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

返回包含形状填充格式属性的 FillFormat 对象。只读 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回：**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

返回形状缩略图。默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。

**返回：**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

返回形状缩略图。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bounds | int | Shape 缩略图边界类型。 |
| scaleX | float | X 缩放 |
| scaleY | float | Y 缩放 |

**返回：**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail or null in case when ShapeThumbnailBounds.Appearance is used and a shape doesn't have visible elements.

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

确定形状是否隐藏。可读写 boolean。

**返回：**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

确定形状是否隐藏。可读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

返回形状在 Z 顺序中的位置。Shapes[0] 返回 Z 顺序最底部的形状，Shapes[Shapes.Count - 1] 返回 Z 顺序最前面的形状。只读 int。

**返回：**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

返回形状的连接点数量。只读 int。

**返回：**
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

返回或设置指定形状绕 Z 轴旋转的角度（度）。正值表示顺时针旋转；负值表示逆时针旋转。可读写 float。

返回的值始终已定义（不是 Float.NaN）。赋值必须已定义（不是 Float.NaN）。可以为 RawFrame 实例属性设置未定义的值。

**返回：**
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

返回或设置指定形状绕 Z 轴旋转的角度（度）。正值表示顺时针旋转；负值表示逆时针旋转。可读写 float。

赋值必须已定义（不是 Float.NaN）。可以为 RawFrame 实例属性设置未定义的值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

获取或设置形状左上角的 X 坐标（以点为单位）。可读写 float。

返回的值始终已定义且永不为 Float.NaN。赋值时也必须已定义；仅在 RawFrame 实例属性中才可赋值 Float.NaN。

**返回：**
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

获取或设置形状左上角的 X 坐标（以点为单位）。可读写 float。

返回的值始终已定义且永不为 Float.NaN。赋值时也必须已定义；仅在 RawFrame 实例属性中才可赋值 Float.NaN。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

获取或设置形状左上角的 Y 坐标（以点为单位）。可读写 float。

返回的值始终已定义且永不为 Float.NaN。赋值时也必须已定义；仅在 RawFrame 实例属性中才可赋值 Float.NaN。

**返回：**
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

获取或设置形状左上角的 Y 坐标（以点为单位）。可读写 float。

返回的值始终已定义且永不为 Float.NaN。赋值时也必须已定义；仅在 RawFrame 实例属性中才可赋值 Float.NaN。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

获取或设置形状的宽度（以点为单位）。可读写 float。

返回的值始终已定义且永不为 Float.NaN。赋值时也必须已定义；仅在 RawFrame 实例属性中才可赋值 Float.NaN。

**返回：**
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

获取或设置形状的宽度（以点为单位）。可读写 float。

返回的值始终已定义且永不为 Float.NaN。赋值时也必须已定义；仅在 RawFrame 实例属性中才可赋值 Float.NaN。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

获取或设置形状的高度（以点为单位）。可读写 float。

返回的值始终已定义且永不为 Float.NaN。赋值时也必须已定义；仅在 RawFrame 实例属性中才可赋值 Float.NaN。

**返回：**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

获取或设置形状的高度（以点为单位）。可读写 float。

返回的值始终已定义且永不为 Float.NaN。赋值时也必须已定义；仅在 RawFrame 实例属性中才可赋值 Float.NaN。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

返回或设置与形状关联的备用文本。可读写 String。

**返回：**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

返回或设置与形状关联的备用文本。可读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

返回或设置与形状关联的备用文本标题。可读写 String。

**返回：**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

返回或设置与形状关联的备用文本标题。可读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

返回或设置形状的名称。可读写 String。

**返回：**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

返回或设置形状的名称。可读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

获取或设置“标记为装饰性”选项的可读写 boolean。

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回：**
boolean

### setDecorative(boolean value) {#setDecorative-boolean-}
```
public abstract void setDecorative(boolean value)
```

获取或设置“标记为装饰性”选项的可读写 boolean。

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public abstract IBaseShapeLock getShapeLock()
```

返回形状的锁定状态。只读 [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)。

**返回：**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

返回内部的、面向演示文稿的标识符，供插件或其他代码使用。由于该值可能被用户或程序重新分配，不能将其视为持久唯一键。只读 long。另见 \#getOfficeInteropShapeId.getOfficeInteropShapeId。

**返回：**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

返回在幻灯片范围内唯一的标识符，在形状的整个生命周期内保持不变，使 PowerPoint 或互操作代码能够从文档的任何位置可靠地引用该形状。只读 long。另见 \#getUniqueId.getUniqueId。

**返回：**
long

### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

确定形状是否被分组。只读 boolean。

属性 \#getParentGroup.getParentGroup 返回父 GroupShape 对象（如果形状被分组）。

**返回：**
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

属性指定形状在黑白显示模式下的渲染方式。可读写 [BlackWhiteMode](../../com.aspose.slides/blackwhitemode)。

**返回：**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

属性指定形状在黑白显示模式下的渲染方式。可读写 [BlackWhiteMode](../../com.aspose.slides/blackwhitemode)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

如果形状被分组，则返回父 GroupShape 对象。否则返回 null。只读 [IGroupShape](../../com.aspose.slides/igroupshape)。

属性 \#isGrouped.isGrouped 确定形状是否被分组。

**返回：**
[IGroupShape](../../com.aspose.slides/igroupshape)

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

将 Shape 内容保存为 SVG 文件。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目标流 |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

将 Shape 内容保存为 SVG 文件。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目标流 |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 生成选项 |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```

返回基本占位符形状（来自布局和/或母版幻灯片的形状，当前形状从中继承）。

> ```
> // 获取占位符形状的所有（母版/布局/幻灯片）动画效果
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


如果当前形状未继承，则返回 null。

**返回：**
[IShape](../../com.aspose.slides/ishape)