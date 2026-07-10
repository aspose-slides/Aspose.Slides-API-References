---
title: SummaryZoomFrame
second_title: Aspose.Slides for Android via Java API 参考
description: 表示幻灯片中的 Summary Zoom 对象。
type: docs
url: /zh/com.aspose.slides/summaryzoomframe/
---
**继承：**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**所有实现的接口：**
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

表示幻灯片中的 Summary Zoom 对象。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getLayout()](#getLayout--) | 获取框架中 Summary Zoom Sections 的布局。 |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | 获取 Summary Zoom Frame 对象的 [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)。 |
### getLayout() {#getLayout--}
```
public final int getLayout()
```


获取框架中 Summary Zoom Sections 的布局。默认值为 GridLayout。

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

**Returns:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()


获取 Summary Zoom Frame 对象的 [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)。

--------------------

> ```
> 示例演示如何按索引获取 Summary Zoom Section 元素：
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