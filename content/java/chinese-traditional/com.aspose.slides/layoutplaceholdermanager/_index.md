---
title: LayoutPlaceholderManager
second_title: Aspose.Slides for Java API 參考
description: 表示允許您向佈局投影片新增佔位符的管理器。
type: docs
url: /zh-hant/com.aspose.slides/layoutplaceholdermanager/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

表示允許您向佈局投影片新增佔位符的管理器。
## 方法

| 方法 | 說明 |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | 將新佔位符形狀新增至佈局投影片，以容納內容，例如圖片、表格、媒體或文字。 |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | 將新佔位符形狀新增至佈局投影片，以垂直方向容納內容，例如圖片、表格、媒體或文字。 |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | 將新佔位符形狀新增至佈局投影片，以容納文字內容。 |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | 將新佔位符形狀新增至佈局投影片，以垂直方向容納文字內容。 |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | 將新佔位符形狀新增至佈局投影片，以容納圖片。 |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | 將新佔位符形狀新增至佈局投影片，以容納圖表。 |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | 將新佔位符形狀新增至佈局投影片，以容納表格。 |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | 將新佔位符形狀新增至佈局投影片，以容納 SmartArt 圖表。 |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | 將新佔位符形狀新增至佈局投影片，以容納媒體物件。 |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | 將新佔位符形狀新增至佈局投影片，以容納線上影像。 |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```


將新佔位符形狀新增至佈局投影片，以容納內容，例如圖片、表格、媒體或文字。

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

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 座標。 |
| y | float | 新佔位符形狀的 Y 座標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**傳回值：**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立 [IAutoShape](../../com.aspose.slides/iautoshape)，具 Content 佔位符。
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```


將新佔位符形狀新增至佈局投影片，以垂直方向容納內容，例如圖片、表格、媒體或文字。

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

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 座標。 |
| y | float | 新佔位符形狀的 Y 座標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**傳回值：**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立 [IAutoShape](../../com.aspose.slides/iautoshape)，具 Content (Vertical) 佔位符。
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```


將新佔位符形狀新增至佈局投影片，以容納文字內容。

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

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 座標。 |
| y | float | 新佔位符形狀的 Y 座標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**傳回值：**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立 [IAutoShape](../../com.aspose.slides/iautoshape)，具 Text 佔位符。
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```


將新佔位符形狀新增至佈局投影片，以垂直方向容納文字內容。

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

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 座標。 |
| y | float | 新佔位符形狀的 Y 座標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**傳回值：**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立 [IAutoShape](../../com.aspose.slides/iautoshape)，具 Text (Vertical) 佔位符。
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```


將新佔位符形狀新增至佈局投影片，以容納圖片。

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

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 座標。 |
| y | float | 新佔位符形狀的 Y 座標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**傳回值：**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立 [IAutoShape](../../com.aspose.slides/iautoshape)，具 Picture 佔位符。
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```


將新佔位符形狀新增至佈局投影片，以容納圖表。

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


**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 座標。 |
| y | float | 新佔位符形狀的 Y 座標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**傳回值：**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立 [IAutoShape](../../com.aspose.slides/iautoshape)，具 Chart 佔位符。
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```


將新佔位符形狀新增至佈局投影片，以容納表格。

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

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 座標。 |
| y | float | 新佔位符形狀的 Y 座標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**傳回值：**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立 [IAutoShape](../../com.aspose.slides/iautoshape)，具 Table 佔位符。
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```


將新佔位符形狀新增至佈局投影片，以容納 SmartArt 圖表。

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

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 座標。 |
| y | float | 新佔位符形狀的 Y 座標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**傳回值：**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立 [IAutoShape](../../com.aspose.slides/iautoshape)，具 SmartArt 佔位符。
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```


將新佔位符形狀新增至佈局投影片，以容納媒體物件。

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

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 座標。 |
| y | float | 新佔位符形狀的 Y 座標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**傳回值：**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立 [IAutoShape](../../com.aspose.slides/iautoshape)，具 Media 佔位符。
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```


將新佔位符形狀新增至佈局投影片，以容納線上影像。

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

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 座標。 |
| y | float | 新佔位符形狀的 Y 座標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**傳回值：**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立 [IAutoShape](../../com.aspose.slides/iautoshape)，具 Online Image 佔位符。