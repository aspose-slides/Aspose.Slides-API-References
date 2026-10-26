---
title: LayoutPlaceholderManager
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示允許您向版面投影片新增佔位符的管理器。
type: docs
url: /zh-hant/com.aspose.slides/layoutplaceholdermanager/
---
**繼承:**
java.lang.Object

**所有實作的介面:**
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

表示允許您向版面投影片新增佔位符的管理器。
## 方法

| 方法 | 說明 |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | 新增一個佔位符形狀至版面投影片，用於容納內容，例如圖片、表格、媒體或文字。 |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | 新增一個佔位符形狀至版面投影片，以垂直方向容納內容，例如圖片、表格、媒體或文字。 |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | 新增一個佔位符形狀至版面投影片，用於容納文字內容。 |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | 新增一個佔位符形狀至版面投影片，以垂直方向容納文字內容。 |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | 新增一個佔位符形狀至版面投影片，用於容納圖片。 |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | 新增一個佔位符形狀至版面投影片，用於容納圖表。 |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | 新增一個佔位符形狀至版面投影片，用於容納表格。 |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | 新增一個佔位符形狀至版面投影片，用於容納 SmartArt 圖表。 |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | 新增一個佔位符形狀至版面投影片，用於容納媒體物件。 |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | 新增一個佔位符形狀至版面投影片，用於容納線上圖像。 |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

新增一個佔位符形狀至版面投影片，用於容納內容，例如圖片、表格、媒體或文字。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 坐標。 |
| y | float | 新佔位符形狀的 Y 坐標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**傳回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立帶有內容佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

新增一個佔位符形狀至版面投影片，以垂直方向容納內容，例如圖片、表格、媒體或文字。

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
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立帶有內容（垂直）佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

新增一個佔位符形狀至版面投影片，用於容納文字內容。

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
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立帶有文字佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

新增一個佔位符形狀至版面投影片，以垂直方向容納文字內容。

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


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 坐標。 |
| y | float | 新佔位符形狀的 Y 坐標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**傳回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立帶有文字（垂直）佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

新增一個佔位符形狀至版面投影片，用於容納圖片。

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
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立帶有圖片佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

新增一個佔位符形狀至版面投影片，用於容納圖表。

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
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立帶有圖表佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

新增一個佔位符形狀至版面投影片，用於容納表格。

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
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立帶有表格佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

新增一個佔位符形狀至版面投影片，用於容納 SmartArt 圖表。

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
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立帶有 SmartArt 佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

新增一個佔位符形狀至版面投影片，用於容納媒體物件。

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
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立帶有媒體佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

新增一個佔位符形狀至版面投影片，用於容納線上圖像。

--------------------

> ```
> 以下範例示範如何將線上圖像佔位符形狀新增至版面投影片。
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
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立帶有線上圖像佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。