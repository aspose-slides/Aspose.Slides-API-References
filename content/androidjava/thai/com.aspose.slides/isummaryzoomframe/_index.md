---
title: ISummaryZoomFrame
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงเฟรม Summary Zoom ในสไลด์.
type: docs
url: /th/com.aspose.slides/isummaryzoomframe/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicObject
```

แสดงถึงเฟรม Summary Zoom ในสไลด์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getLayout()](#getLayout--) | รับเค้าโครงของส่วน Summary Zoom ในเฟรม. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | รับ [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) สำหรับอ็อบเจกต์ Summary Zoom Frame. |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

รับเค้าโครงของส่วน Summary Zoom ในเฟรม. ค่าเริ่มต้นคือ GridLayout.

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

**คืนค่า:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()
```

รับ [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) สำหรับอ็อบเจกต์ Summary Zoom Frame.

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

**คืนค่า:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)