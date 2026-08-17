---
title: ISummaryZoomFrame
second_title: Aspose.Slides for Java API 参考
description: 表示幻灯片中的 Summary Zoom 帧。
type: docs
url: /zh/com.aspose.slides/isummaryzoomframe/
---
**所有已实现的接口：**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

表示幻灯片中的 Summary Zoom 帧。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLayout()](#getLayout--) | 获取帧中 Summary Zoom 部分的布局。 |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | 获取 Summary Zoom Frame 对象的 [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)。 |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

获取帧中 Summary Zoom 部分的布局。默认值是 GridLayout.

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

**返回：**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()
```

获取 Summary Zoom Frame 对象的 [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)。

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)