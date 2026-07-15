---
title: ISummaryZoomFrame
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Biểu diễn một khung Summary Zoom trong slide.
type: docs
url: /vi/com.aspose.slides/isummaryzoomframe/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

Biểu diễn một khung Summary Zoom trong một slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getLayout()](#getLayout--) | Lấy bố cục của các phần Summary Zoom trong khung. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Lấy [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) cho đối tượng Summary Zoom Frame. |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


Lấy bố cục của các phần Summary Zoom trong khung. Giá trị mặc định là GridLayout.

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

**Trả về:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()
```


Lấy [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) cho đối tượng Summary Zoom Frame.

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

**Trả về:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)