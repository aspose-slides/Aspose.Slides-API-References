---
title: ISummaryZoomFrame
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึง Summary Zoom frame ในสไลด์.
type: docs
url: /th/com.aspose.slides/isummaryzoomframe/
---
**ส่วนต่อประสานที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

เป็น Summary Zoom frame ในสไลด์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getLayout()](#getLayout--) | รับค่าเค้าโครงของ Summary Zoom Sections ในเฟรม |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | รับค่า [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) สำหรับอ็อบเจ็กต์ Summary Zoom Frame |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

รับค่าเค้าโครงของ Summary Zoom Sections ในเฟรม ค่าเริ่มต้นคือ GridLayout.

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

**ผลลัพธ์:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()
```

รับค่า [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) สำหรับอ็อบเจ็กต์ Summary Zoom Frame

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

**ผลลัพธ์:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)