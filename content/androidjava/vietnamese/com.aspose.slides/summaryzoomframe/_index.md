---
title: SummaryZoomFrame
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một đối tượng Summary Zoom trong một slide.
type: docs
url: /vi/com.aspose.slides/summaryzoomframe/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

Biểu diễn một đối tượng Summary Zoom trong một slide.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getLayout()](#getLayout--) | Lấy bố cục của các phần Summary Zoom trong khung. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Lấy [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) cho đối tượng Summary Zoom Frame. |

### getLayout() {#getLayout--}
```
public final int getLayout()
```

Lấy bố cục của các phần Summary Zoom trong khung. Giá trị mặc định là GridLayout.

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

**Trả về:**
int

### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```

Lấy [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) cho đối tượng Summary Zoom Frame.

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

**Trả về:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)