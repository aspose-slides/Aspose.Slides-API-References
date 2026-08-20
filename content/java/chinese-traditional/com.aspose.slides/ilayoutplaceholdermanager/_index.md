---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Java API Reference
description: 代表允許您向版面投影片添加佔位符的管理器。
type: docs
url: /zh-hant/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

代表允許您向版面投影片添加佔位符的管理器。
## 方法

| 方法 | 說明 |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | 在版面投影片上新增一個佔位符形狀，用於保存內容，例如圖片、表格、媒體或文字。 |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | 在版面投影片上新增一個佔位符形狀，用於保存內容，例如圖片、表格、媒體或文字（垂直方向）。 |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | 在版面投影片上新增一個佔位符形狀，用於保存文字內容。 |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | 在版面投影片上新增一個佔位符形狀，用於保存文字內容（垂直方向）。 |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | 在版面投影片上新增一個佔位符形狀，用於保存圖片。 |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | 在版面投影片上新增一個佔位符形狀，用於保存圖表。 |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | 在版面投影片上新增一個佔位符形狀，用於保存表格。 |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | 在版面投影片上新增一個佔位符形狀，用於保存 SmartArt 圖示。 |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | 在版面投影片上新增一個佔位符形狀，用於保存媒體物件。 |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | 在版面投影片上新增一個佔位符形狀，用於保存線上圖片。 |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

在版面投影片上新增一個佔位符形狀，用於保存內容，例如圖片、表格、媒體或文字。

--------------------

> ```
> The following example shows how to add the Content placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addContentPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 坐標。 |
| y | float | 新佔位符形狀的 Y 坐標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**傳回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立具有內容佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

在版面投影片上新增一個佔位符形狀，用於保存內容，例如圖片、表格、媒體或文字（垂直方向）。

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


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 坐標。 |
| y | float | 新佔位符形狀的 Y 坐標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**傳回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立具有內容（垂直）佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

在版面投影片上新增一個佔位符形狀，用於保存文字內容。

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


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 坐標。 |
| y | float | 新佔位符形狀的 Y 坐標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**傳回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立具有文字佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

在版面投影片上新增一個佔位符形狀，用於保存文字內容（垂直方向）。

--------------------

> ```
> The following example shows how to add the Text (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalTextPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 坐標。 |
| y | float | 新佔位符形狀的 Y 坐標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**傳回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立具有文字（垂直）佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

在版面投影片上新增一個佔位符形狀，用於保存圖片。

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


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 坐標。 |
| y | float | 新佔位符形狀的 Y 坐標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**傳回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立具有圖片佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

在版面投影片上新增一個佔位符形狀，用於保存圖表。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 坐標。 |
| y | float | 新佔位符形狀的 Y 坐標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**傳回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立具有圖表佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

在版面投影片上新增一個佔位符形狀，用於保存表格。

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


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 坐標。 |
| y | float | 新佔位符形狀的 Y 坐標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**傳回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立具有表格佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

在版面投影片上新增一個佔位符形狀，用於保存 SmartArt 圖示。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 坐標。 |
| y | float | 新佔位符形狀的 Y 坐標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**傳回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立具有 SmartArt 佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

在版面投影片上新增一個佔位符形狀，用於保存媒體物件。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 坐標。 |
| y | float | 新佔位符形狀的 Y 坐標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**傳回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立具有媒體佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

在版面投影片上新增一個佔位符形狀，用於保存線上圖片。

--------------------

> ```
> The following example shows how to add the Online Image placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addOnlineImagePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 坐標。 |
| y | float | 新佔位符形狀的 Y 坐標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**傳回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立具有線上圖片佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。