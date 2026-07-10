---
title: LayoutPlaceholderManager
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 表示允许向布局幻灯片添加占位符的管理器。
type: docs
url: /zh/com.aspose.slides/layoutplaceholdermanager/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

表示允许向布局幻灯片添加占位符的管理器。
## 方法

| 方法 | 描述 |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | 向布局幻灯片添加新的占位符形状以容纳内容，例如图片、表格、媒体或文本。 |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | 向布局幻灯片添加新的占位符形状以垂直方向容纳内容，例如图片、表格、媒体或文本。 |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | 向布局幻灯片添加新的占位符形状以容纳文本内容。 |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | 向布局幻灯片添加新的占位符形状以垂直方向容纳文本内容。 |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | 向布局幻灯片添加新的占位符形状以容纳图片。 |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | 向布局幻灯片添加新的占位符形状以容纳图表。 |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | 向布局幻灯片添加新的占位符形状以容纳表格。 |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | 向布局幻灯片添加新的占位符形状以容纳 SmartArt 图表。 |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | 向布局幻灯片添加新的占位符形状以容纳媒体对象。 |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | 向布局幻灯片添加新的占位符形状以容纳在线图像。 |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

向布局幻灯片添加新的占位符形状以容纳内容，例如图片、表格、媒体或文本。

--------------------

> ```
> The following example shows how to add the Content placeholder shape to the layout slide.
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addContentPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Content placeholder.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Adds a new placeholder shape to the layout slide to hold content, such as a picture, table, media or text in a vertical direction.

--------------------

> ```
> The following example shows how to add the Content (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalContentPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Content (Vertical) placeholder.
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Adds a new placeholder shape to the layout slide to hold text content.

--------------------

> ```
> The following example shows how to add the Text placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Text placeholder.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Adds a new placeholder shape to the layout slide to hold text content in a vertical direction.

--------------------

> ```
> The following example shows how to add the Text (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Text (Vertical) placeholder.
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Adds a new placeholder shape to the layout slide to hold a picture.

--------------------

> ```
> The following example shows how to add the Picture placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addPicturePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Picture placeholder.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Adds a new placeholder shape to the layout slide to hold a chart.

--------------------

> ```
> The following example shows how to add the Chart placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addChartPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Chart placeholder.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Adds a new placeholder shape to the layout slide to hold a table.

--------------------

> ```
> The following example shows how to add the Table placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTablePlaceholder(20, 20, 500, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Table placeholder.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Adds a new placeholder shape to the layout slide to hold a SmartArt diagram.

--------------------

> ```
> The following example shows how to add the SmartArt placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addSmartArtPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a SmartArt placeholder.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Adds a new placeholder shape to the layout slide to hold a media object.

--------------------

> ```
> The following example shows how to add the Media placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addMediaPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Media placeholder.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)

向布局幻灯片添加新的占位符形状以容纳在线图像。

--------------------

> ```
> The following example shows how to add the Online Image placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addOnlineImagePlaceholder(20, 20, 200, 200);
>  } finally {
>      if ( pres != null ) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新占位符形状的 X 坐标。 |
| y | float | 新占位符形状的 Y 坐标。 |
| width | float | 新占位符形状的宽度。 |
| height | float | 新占位符形状的高度。 |

**返回值：**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已创建 [IAutoShape](../../com.aspose.slides/iautoshape)，使用在线图像占位符。