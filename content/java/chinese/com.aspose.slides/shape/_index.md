---
title: Shape
second_title: Aspose.Slides Java API 参考
description: 表示幻灯片上的形状。
type: docs
url: /zh/com.aspose.slides/shape/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject  
```
public class Shape implements IShape, IDOMObject
```

表示幻灯片上的形状。

## 方法

| 方法 | 描述 |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | 确定形状是否为 TextHolder_PPT。 |
| [getPlaceholder()](#getPlaceholder--) | 返回形状的占位符。 |
| [removePlaceholder()](#removePlaceholder--) | 定义此形状不是占位符。 |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | 如果不存在，则添加一个新的占位符并将占位符属性设置为指定的占位符。 |
| [getBasePlaceholder()](#getBasePlaceholder--) | 返回基本占位符形状（从布局和/或母版幻灯片继承的当前形状）。 |
| [getCustomData()](#getCustomData--) | 返回形状的自定义数据。 |
| [getRawFrame()](#getRawFrame--) | 返回或设置原始形状框架的属性。 |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | 返回或设置原始形状框架的属性。 |
| [getFrame()](#getFrame--) | 返回或设置原始形状框架的属性。 |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | 返回或设置原始形状框架的属性。 |
| [getLineFormat()](#getLineFormat--) | 返回包含形状线条格式属性的 LineFormat 对象。 |
| [getThreeDFormat()](#getThreeDFormat--) | 返回包含形状 3D 效果属性的 ThreeDFormat 对象。 |
| [getEffectFormat()](#getEffectFormat--) | 返回包含应用于形状的像素效果的 EffectFormat 对象。 |
| [getFillFormat()](#getFillFormat--) | 返回包含形状填充格式属性的 FillFormat 对象。 |
| [getImage()](#getImage--) | 返回形状缩略图。 |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | 返回形状缩略图。 |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | 将 Shape 内容保存为 SVG 文件。 |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | 将 Shape 内容保存为 SVG 文件。 |
| [getHyperlinkClick()](#getHyperlinkClick--) | 返回或设置用于鼠标点击的超链接。 |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | 返回或设置用于鼠标点击的超链接。 |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | 返回或设置用于鼠标悬停的超链接。 |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | 返回或设置用于鼠标悬停的超链接。 |
| [getHyperlinkManager()](#getHyperlinkManager--) | 返回超链接管理器。 |
| [getHidden()](#getHidden--) | 确定形状是否隐藏。 |
| [setHidden(boolean value)](#setHidden-boolean-) | 确定形状是否隐藏。 |
| [getZOrderPosition()](#getZOrderPosition--) | 返回形状在 Z 顺序中的位置。 |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | 返回形状的连接点数量。 |
| [getRotation()](#getRotation--) | 返回或设置指定形状绕 Z 轴旋转的度数。 |
| [setRotation(float value)](#setRotation-float-) | 返回或设置指定形状绕 Z 轴旋转的度数。 |
| [getX()](#getX--) | 获取或设置形状左上角的 X 坐标（以点为单位）。 |
| [setX(float value)](#setX-float-) | 获取或设置形状左上角的 X 坐标（以点为单位）。 |
| [getY()](#getY--) | 获取或设置形状左上角的 Y 坐标（以点为单位）。 |
| [setY(float value)](#setY-float-) | 获取或设置形状左上角的 Y 坐标（以点为单位）。 |
| [getWidth()](#getWidth--) | 获取或设置形状的宽度（以点为单位）。 |
| [setWidth(float value)](#setWidth-float-) | 获取或设置形状的宽度（以点为单位）。 |
| [getHeight()](#getHeight--) | 获取或设置形状的高度（以点为单位）。 |
| [setHeight(float value)](#setHeight-float-) | 获取或设置形状的高度（以点为单位）。 |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | 属性指定形状在黑白显示模式下的呈现方式。 |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | 属性指定形状在黑白显示模式下的呈现方式。 |
| [getUniqueId()](#getUniqueId--) | 返回内部的、针对演示文稿范围的标识符，供加载项或其他代码使用。 |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | 返回一个针对幻灯片范围的唯一标识符，在形状的整个生命周期内保持不变，使 PowerPoint 或互操作代码能够可靠地从文档任何位置引用该形状。 |
| [getAlternativeText()](#getAlternativeText--) | 返回或设置与形状关联的替代文本。 |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 返回或设置与形状关联的替代文本。 |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | 返回或设置与形状关联的替代文本标题。 |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | 返回或设置与形状关联的替代文本标题。 |
| [getName()](#getName--) | 返回或设置形状的名称。 |
| [setName(String value)](#setName-java.lang.String-) | 返回或设置形状的名称。 |
| [isDecorative()](#isDecorative--) | 获取或设置“标记为装饰性”的选项，读/写布尔值。 |
| [setDecorative(boolean value)](#setDecorative-boolean-) | 获取或设置“标记为装饰性”的选项，读/写布尔值。 |
| [getShapeLock()](#getShapeLock--) | 返回形状的锁定状态。 |
| [isGrouped()](#isGrouped--) | 确定形状是否已分组。 |
| [getParentGroup()](#getParentGroup--) | 如果形状已分组，返回父 GroupShape 对象。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | 获取根据渲染内容计算的形状视觉边界。 |
| [getSlide()](#getSlide--) | 返回形状的父幻灯片。 |
| [getPresentation()](#getPresentation--) | 返回幻灯片的父演示文稿。 |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

确定形状是否为 TextHolder_PPT。只读 boolean 。

**返回:**  
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

返回形状的占位符。如果形状没有占位符，则返回 null。只读 [IPlaceholder](../../com.aspose.slides/iplaceholder)。

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // 实例化一个 Presentation 类
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // 访问第一张幻灯片
>      ISlide sld = pres.getSlides().get_Item(0);
>      // 迭代形状以查找占位符
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // 更改每个占位符中的文本
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // 将演示文稿保存到磁盘
>      pres.save("output_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set Prompt Text in Placeholder.
>  
>  Presentation pres = new Presentation("Presentation2.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      for (IShape shape : slide.getSlide().getShapes()) // 迭代幻灯片
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint 显示 “单击添加标题”
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // 添加副标题
>              {
>                  text = "Add Subtitle";
>              }
>              ((IAutoShape)shape).getTextFrame().setText(text);
>              System.out.println("Placeholder with text: " + text);
>          }
>      }
>      pres.save("Placeholders_PromptText.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回:**  
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

定义此形状不是占位符。

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

如果不存在，则添加一个新的占位符并将占位符属性设置为指定的占位符。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | 要从中复制内容的占位符。 |

**返回:**  
[IPlaceholder](../../com.aspose.slides/iplaceholder) - 新 \#getPlaceholder.getPlaceholder。

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

返回基本占位符形状（从布局和/或母版幻灯片继承的当前形状）。

--------------------

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


--------------------

如果当前形状未继承，则返回 null。

**返回:**  
[IShape](../../com.aspose.slides/ishape)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

返回形状的自定义数据。只读 [ICustomData](../../com.aspose.slides/icustomdata)。

**返回:**  
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

返回或设置原始形状框架的属性。读/写 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

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
>  //But IShape.RawFrame frame properties can be undefined. This make sence when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // now shape inherits x, y, height, flipH, flipV values form placeholder and overrides width=100 and rotationAngle=0.{code}
> ```

**返回:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

返回或设置原始形状框架的属性。读/写 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

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
>  //But IShape.RawFrame frame properties can be undefined. This make sence when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // now shape inherits x, y, height, flipH, flipV values form placeholder and overrides width=100 and rotationAngle=0.{code}
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

返回或设置形状框架的属性。读/写 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

--------------------

返回的 IShapeFrame 实例的每个属性值均已定义（不是 Float.NaN 或 NotDefined）。分配的 IShapeFrame 实例的每个属性值必须已定义（不是 Float.NaN 或 NotDefined）。您可以为 RawFrame 实例属性设置未定义值。

**返回:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

返回或设置形状框架的属性。读/写 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

--------------------

返回值始终已定义（不是 Float.NaN）。分配的值必须已定义（不是 Float.NaN）。您可以为 RawFrame 实例属性设置未定义值。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

返回包含形状线条格式属性的 LineFormat 对象。注意：对于没有线条属性的某些类型形状，可能返回 null。只读 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

返回包含形状 3D 效果属性的 ThreeDFormat 对象。注意：对于没有 3D 属性的某些类型形状，可能返回 null。只读 [IThreeDFormat](../../com.aspose.slides/ithreedformat)。

**返回:**  
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

返回包含应用于形状的像素效果的 EffectFormat 对象。注意：对于没有效果属性的某些类型形状，可能返回 null。只读 [IEffectFormat](../../com.aspose.slides/ieffectformat)。

**返回:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

返回包含形状填充格式属性的 FillFormat 对象。注意：对于没有填充属性的某些类型形状，可能返回 null。只读 [IFillFormat](../../com.aspose.slides/ifillformat)。

--------------------

> ```
> The following example shows how to change the accent color for a theme of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      shape.getFillFormat().setFillType(FillType.Solid);
>      shape.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example demonstrates how to obtain palette colors from the main theme color and then used in shapes.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Accent 4
>      IShape shape1 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 50, 50);
>      shape1.getFillFormat().setFillType(FillType.Solid);
>      shape1.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      // Accent 4, Lighter 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Accent 4, Lighter 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Accent 4, Lighter 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Accent 4, Darker 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Accent 4, Darker 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public final IImage getImage()
```

返回形状缩略图。默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。

**返回:**  
[IImage](../../com.aspose.slides/iimage) - 形状缩略图。

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

返回形状缩略图。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bounds | int | 形状缩略图边界类型。 |
| scaleX | float | X 缩放 |
| scaleY | float | Y 缩放 |

**返回:**  
[IImage](../../com.aspose.slides/iimage) - 形状缩略图；如果使用 ShapeThumbnailBounds.Appearance 且形状没有可见元素，则返回 null。

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

将 Shape 内容保存为 SVG 文件。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目标流 |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

将 Shape 内容保存为 SVG 文件。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目标流 |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 生成选项 |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

返回或设置用于鼠标点击的超链接。读/写 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**返回:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

返回或设置用于鼠标点击的超链接。读/写 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

返回或设置用于鼠标悬停的超链接。读/写 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**返回:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

返回或设置用于鼠标悬停的超链接。读/写 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

返回超链接管理器。只读 [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)。

**返回:**  
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

确定形状是否隐藏。读/写 boolean 。

**返回:**  
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

确定形状是否隐藏。读/写 boolean 。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

返回形状在 Z 顺序中的位置。Shapes[0] 返回 Z 顺序最后面的形状，Shapes[Shapes.Count - 1] 返回最前面的形状。只读 int 。

**返回:**  
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

返回形状的连接点数量。只读 int 。

**返回:**  
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

返回或设置指定形状绕 Z 轴旋转的度数。正值表示顺时针旋转；负值表示逆时针旋转。读/写 float。

--------------------

返回值始终已定义（不是 Float.NaN）。分配的值必须已定义（不是 Float.NaN）。您可以为 RawFrame 实例属性设置未定义值。

**返回:**  
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```
Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. 读写 float.

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

获取或设置形状左上角的 X 坐标，以点为单位。读写 float.

--------------------

返回的值始终已定义且从不为 Float.NaN。赋值的值也必须已定义；仅对 RawFrame 实例的属性赋值 Float.NaN。

**返回值:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

获取或设置形状左上角的 X 坐标，以点为单位。读写 float.

--------------------

返回的值始终已定义且从不为 Float.NaN。赋值的值也必须已定义；仅对 RawFrame 实例的属性赋值 Float.NaN。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

获取或设置形状左上角的 Y 坐标，以点为单位。读写 float.

--------------------

返回的值始终已定义且从不为 Float.NaN。赋值的值也必须已定义；仅对 RawFrame 实例的属性赋值 Float.NaN。

**返回值:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

获取或设置形状左上角的 Y 坐标，以点为单位。读写 float.

--------------------

返回的值始终已定义且从不为 Float.NaN。赋值的值也必须已定义；仅对 RawFrame 实例的属性赋值 Float.NaN。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

获取或设置形状的宽度，以点为单位。读写 float.

--------------------

返回的值始终已定义且从不为 Float.NaN。赋值的值也必须已定义；仅对 RawFrame 实例的属性赋值 Float.NaN。

**返回值:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

获取或设置形状的宽度，以点为单位。读写 float.

--------------------

返回的值始终已定义且从不为 Float.NaN。赋值的值也必须已定义；仅对 RawFrame 实例的属性赋值 Float.NaN。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

获取或设置形状的高度，以点为单位。读写 float.

--------------------

返回的值始终已定义且从不为 Float.NaN。赋值的值也必须已定义；仅对 RawFrame 实例的属性赋值 Float.NaN。

**返回值:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

获取或设置形状的高度，以点为单位。读写 float.

--------------------

返回的值始终已定义且从不为 Float.NaN。赋值的值也必须已定义；仅对 RawFrame 实例的属性赋值 Float.NaN。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

属性指定形状在黑白显示模式下的渲染方式.. 读写 [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**返回值:**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

属性指定形状在黑白显示模式下的渲染方式.. 读写 [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

返回一个内部的、针对演示文稿范围的标识符，供加载项或其他代码使用。由于该值可能被用户或程序重新分配，不能将其视为持久唯一键。只读 long。另请参阅 \#getOfficeInteropShapeId.getOfficeInteropShapeId。

**返回值:**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

返回一个针对幻灯片范围的唯一标识符，在形状的整个生命周期内保持不变，让 PowerPoint 或互操作代码能够在文档的任何位置可靠地引用该形状。只读 long。另请参阅 \#getUniqueId.getUniqueId。

**返回值:**
long
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

返回或设置与形状关联的替代文本。读写 String。

**返回值:**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

返回或设置与形状关联的替代文本。读写 String。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

返回或设置与形状关联的替代文本的标题。读写 String。

**返回值:**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

返回或设置与形状关联的替代文本的标题。读写 String。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

返回或设置形状的名称。不能为空。如有需要请使用空字符串。读写 String。

**返回值:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

返回或设置形状的名称。不能为空。如有需要请使用空字符串。读写 String。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

获取或设置“标记为装饰性”选项。读写 boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回值:**
boolean
### setDecorative(boolean value) {#setDecorative-boolean-}
```
public final void setDecorative(boolean value)
```

获取或设置“标记为装饰性”选项。读写 boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public IBaseShapeLock getShapeLock()
```

返回形状的锁定状态。只读 [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)。

**返回值:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

确定形状是否已分组。只读 boolean.

--------------------

属性 \#getParentGroup.getParentGroup 在形状已分组时返回父 GroupShape 对象。

**返回值:**
boolean
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

如果形状已分组，则返回父 GroupShape 对象。否则返回 null。只读 [IGroupShape](../../com.aspose.slides/igroupshape)。

--------------------

属性 \#isGrouped.isGrouped 确定形状是否已分组。

**返回值:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回值:**
com.aspose.slides.IDOMObject
### getVisualBounds() {#getVisualBounds--}
```
public final Rectangle2D.Float getVisualBounds()
```

获取根据渲染内容计算得到的形状可视边界。

**返回值:**
java.awt.geom.Rectangle2D.Float - 表示形状在幻灯片坐标系中可视边界的 java.awt.geom.Rectangle2D.Float。

--------------------

返回的矩形表示在幻灯片坐标空间中形状渲染期间产生的所有内容的轴对齐边界。这些边界可能不同于形状的模型边界 \#getX.getX/\#setX(float).setX(float)、\#getY.getY/\#setY(float).setY(float)、\#getWidth.getWidth/\#setWidth(float).setWidth(float) 和 \#getHeight.getHeight/\#setHeight(float).setHeight(float)，如果渲染内容超出幻灯片原点，边界甚至可能包含负坐标。可视边界会考虑渲染相关的因素，例如变换（如旋转）、笔画宽度和连接、文本布局与溢出、SmartArt 几何形状以及其他影响形状最终渲染外观的布局效果。返回的边界不会被裁剪到幻灯片矩形内。
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回形状的父幻灯片。只读 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**返回值:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回幻灯片的父演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回值:**
[IPresentation](../../com.aspose.slides/ipresentation)