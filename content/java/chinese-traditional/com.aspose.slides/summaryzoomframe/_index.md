---
title: SummaryZoomFrame
second_title: Aspose.Slides for Java API 參考
description: 在投影片中表示一個 Summary Zoom 物件。
type: docs
url: /zh-hant/com.aspose.slides/summaryzoomframe/
---
**繼承：**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**所有已實作的介面：**
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

在投影片中表示一個 Summary Zoom 物件。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getLayout()](#getLayout--) | 取得框架中 Summary Zoom 部分的佈局。 |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | 取得 [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) 用於 Summary Zoom Frame 物件。 |
### getLayout() {#getLayout--}
```
public final int getLayout()
```

取得框架中 Summary Zoom 部分的佈局。預設值為 GridLayout。

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>      int layout = zoomFrame.getLayout();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回值：**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```

取得 [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) 用於 Summary Zoom Frame 物件。

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>      ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回值：**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)