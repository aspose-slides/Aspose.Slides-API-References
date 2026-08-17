---
title: LayoutPlaceholderManager
second_title: Aspose.Slides for Java API 参考
description: 表示一个管理器，允许您向布局幻灯片添加占位符。
type: docs
url: /zh/com.aspose.slides/layoutplaceholdermanager/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

表示允许您向布局幻灯片添加占位符的管理器。
## 方法

| 方法 | 描述 |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | 向布局幻灯片添加新的占位符形状以容纳内容，例如图片、表格、媒体或文本。 |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | 向布局幻灯片添加新的占位符形状以容纳内容，例如图片、表格、媒体或文本，以垂直方向。 |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | 向布局幻灯片添加新的占位符形状以容纳文本内容。 |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | 向布局幻灯片添加新的占位符形状以容纳文本内容，以垂直方向。 |
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


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新占位符形状的 X 坐标。 |
| y | float | 新占位符形状的 Y 坐标。 |
| width | float | 新占位符形状的宽度。 |
| height | float | 新占位符形状的高度。 |

**返回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已创建 [IAutoShape](../../com.aspose.slides/iautoshape)，包含 Content 占位符。
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```


向布局幻灯片添加新的占位符形状以容纳内容，例如图片、表格、媒体或文本，以垂直方向。

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


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新占位符形状的 X 坐标。 |
| y | float | 新占位符形状的 Y 坐标。 |
| width | float | 新占位符形状的宽度。 |
| height | float | 新占位符形状的高度。 |

**返回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已创建 [IAutoShape](../../com.aspose.slides/iautoshape)，包含 Content (Vertical) 占位符。
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```


向布局幻灯片添加新的占位符形状以容纳文本内容。

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


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新占位符形状的 X 坐标。 |
| y | float | 新占位符形状的 Y 坐标。 |
| width | float | 新占位符形状的宽度。 |
| height | float | 新占位符形状的高度。 |

**返回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已创建 [IAutoShape](../../com.aspose.slides/iautoshape)，包含 Text 占位符。
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```


向布局幻灯片添加新的占位符形状以容纳文本内容，以垂直方向。

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


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新占位符形状的 X 坐标。 |
| y | float | 新占位符形状的 Y 坐标。 |
| width | float | 新占位符形状的宽度。 |
| height | float | 新占位符形状的高度。 |

**返回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已创建 [IAutoShape](../../com.aspose.slides/iautoshape)，包含 Text (Vertical) 占位符。
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```


向布局幻灯片添加新的占位符形状以容纳图片。

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


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新占位符形状的 X 坐标。 |
| y | float | 新占位符形状的 Y 坐标。 |
| width | float | 新占位符形状的宽度。 |
| height | float | 新占位符形状的高度。 |

**返回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已创建 [IAutoShape](../../com.aspose.slides/iautoshape)，包含 Picture 占位符。
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```


向布局幻灯片添加新的占位符形状以容纳图表。

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


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新占位符形状的 X 坐标。 |
| y | float | 新占位符形状的 Y 坐标。 |
| width | float | 新占位符形状的宽度。 |
| height | float | 新占位符形状的高度。 |

**返回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已创建 [IAutoShape](../../com.aspose.slides/iautoshape)，包含 Chart 占位符。
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```


向布局幻灯片添加新的占位符形状以容纳表格。

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


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新占位符形状的 X 坐标。 |
| y | float | 新占位符形状的 Y 坐标。 |
| width | float | 新占位符形状的宽度。 |
| height | float | 新占位符形状的高度。 |

**返回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已创建 [IAutoShape](../../com.aspose.slides/iautoshape)，包含 Table 占位符。
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```


向布局幻灯片添加新的占位符形状以容纳 SmartArt 图表。

--------------------

> ```
> 以下示例展示了如何向布局幻灯片添加 SmartArt 占位符形状。
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addSmartArtPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新占位符形状的 X 坐标。 |
| y | float | 新占位符形状的 Y 坐标。 |
| width | float | 新占位符形状的宽度。 |
| height | float | 新占位符形状的高度。 |

**返回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已创建 [IAutoShape](../../com.aspose.slides/iautoshape)，包含 SmartArt 占位符。
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```


向布局幻灯片添加新的占位符形状以容纳媒体对象。

--------------------

> ```
> 以下示例展示了如何向布局幻灯片添加 Media 占位符形状。
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addMediaPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新占位符形状的 X 坐标。 |
| y | float | 新占位符形状的 Y 坐标。 |
| width | float | 新占位符形状的宽度。 |
| height | float | 新占位符形状的高度。 |

**返回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已创建 [IAutoShape](../../com.aspose.slides/iautoshape)，包含 Media 占位符。
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```


向布局幻灯片添加新的占位符形状以容纳在线图像。

--------------------

> ```
> 以下示例展示了如何向布局幻灯片添加 Online Image 占位符形状。
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addOnlineImagePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新占位符形状的 X 坐标。 |
| y | float | 新占位符形状的 Y 坐标。 |
| width | float | 新占位符形状的宽度。 |
| height | float | 新占位符形状的高度。 |

**返回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已创建 [IAutoShape](../../com.aspose.slides/iautoshape)，包含 Online Image 占位符。