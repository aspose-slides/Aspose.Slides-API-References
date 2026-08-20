---
title: ISummaryZoomFrame
second_title: Aspose.Slides for Java API 參考
description: 表示投影片中的 Summary Zoom 框架。
type: docs
url: /zh-hant/com.aspose.slides/isummaryzoomframe/
---
**已實作的介面：**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

表示投影片中的 Summary Zoom 框架。
## 方法

| Method | Description |
| --- | --- |
| [getLayout()](#getLayout--) | 取得框架中 Summary Zoom Sections 的版面配置。 |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | 取得 Summary Zoom Frame 物件的 [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)。 |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

取得框架中 Summary Zoom Sections 的版面配置。預設值為 GridLayout.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       int layout = zoomFrame.getLayout();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**傳回值：**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()
```

取得 Summary Zoom Frame 物件的 [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)。

--------------------

> ```
> 此範例示範如何依索引取得 Summary Zoom Section 元素：
>  
>  Presentation pres = new Presentation();
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**傳回值：**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)