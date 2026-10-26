---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Android via Java API Reference
description: 表示允許您在佈局投影片中新增佔位符的管理器。
type: docs
url: /zh-hant/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

表示允許您在佈局投影片中新增佔位符的管理器。
## 方法

| 方法 | 說明 |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold content, such as a picture, table, media or text. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold content, such as a picture, table, media or text in a vertical direction. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold text content. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold text content in a vertical direction. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold a picture. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold a chart. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold a table. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold a SmartArt diagram. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold a media object. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold an online image. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

新增一個佔位符形狀到佈局投影片，用於容納內容，例如圖片、表格、媒體或文字。

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
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 座標。 |
| y | float | 新佔位符形狀的 Y 座標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**回傳值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立具內容佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

新增一個佔位符形狀到佈局投影片，用於以垂直方向容納內容，例如圖片、表格、媒體或文字。

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
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 座標。 |
| y | float | 新佔位符形狀的 Y 座標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**回傳值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立具有垂直內容佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

新增一個佔位符形狀到佈局投影片，用於容納文字內容。

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
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 座標。 |
| y | float | 新佔位符形狀的 Y 座標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**回傳值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立具文字佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

新增一個佔位符形狀到佈局投影片，用於以垂直方向容納文字內容。

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
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 座標。 |
| y | float | 新佔位符形狀的 Y 座標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**回傳值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立具有垂直文字佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

新增一個佔位符形狀到佈局投影片，用於容納圖片。

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
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 座標。 |
| y | float | 新佔位符形狀的 Y 座標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**回傳值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立具圖片佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

新增一個佔位符形狀到佈局投影片，用於容納圖表。

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
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 座標。 |
| y | float | 新佔位符形狀的 Y 座標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**回傳值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立具圖表佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

新增一個佔位符形狀到佈局投影片，用於容納表格。

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
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 座標。 |
| y | float | 新佔位符形狀的 Y 座標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**回傳值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立具表格佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

新增一個佔位符形狀到佈局投影片，用於容納 SmartArt 圖表。

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
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 座標。 |
| y | float | 新佔位符形狀的 Y 座標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**回傳值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立具 SmartArt 佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

新增一個佔位符形狀到佈局投影片，用於容納媒體物件。

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
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 座標。 |
| y | float | 新佔位符形狀的 Y 座標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**回傳值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立具媒體佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

新增一個佔位符形狀到佈局投影片，用於容納線上影像。

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
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新佔位符形狀的 X 座標。 |
| y | float | 新佔位符形狀的 Y 座標。 |
| width | float | 新佔位符形狀的寬度。 |
| height | float | 新佔位符形狀的高度。 |

**回傳值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 已建立具線上影像佔位符的 [IAutoShape](../../com.aspose.slides/iautoshape)。