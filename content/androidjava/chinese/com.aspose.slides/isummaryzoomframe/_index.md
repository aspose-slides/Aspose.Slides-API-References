---
title: ISummaryZoomFrame
second_title: Aspose.Slides for Android 的 Java API 参考
description: 表示幻灯片中的 Summary Zoom 框架。
type: docs
url: /zh/com.aspose.slides/isummaryzoomframe/
---
**所有实现的接口：**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

表示幻灯片中的 Summary Zoom 框架。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getLayout()](#getLayout--) | 获取框架中 Summary Zoom Sections 的布局。 |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | 获取 [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) 对于 Summary Zoom Frame 对象。 |

### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

获取框架中 Summary Zoom Sections 的布局。默认值为 GridLayout。

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

**Returns:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()

Gets [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) for the Summary Zoom Frame object.


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

**返回值：**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)