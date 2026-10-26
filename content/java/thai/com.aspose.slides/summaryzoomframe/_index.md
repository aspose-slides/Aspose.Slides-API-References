---
title: SummaryZoomFrame
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: แสดงอ็อบเจ็กต์ Summary Zoom ในสไลด์หนึ่ง.
type: docs
url: /th/com.aspose.slides/summaryzoomframe/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**ส่วนติดต่อที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

แสดงถึงอ็อบเจ็กต์ Summary Zoom ในสไลด์หนึ่ง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getLayout()](#getLayout--) | ดึงการจัดวางของส่วน Summary Zoom ในเฟรม. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | ดึง [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) สำหรับอ็อบเจ็กต์ Summary Zoom Frame. |
### getLayout() {#getLayout--}
```
public final int getLayout()
```

ดึงการจัดวางของส่วน Summary Zoom ในเฟรม. ค่าเริ่มต้นคือ GridLayout.

--------------------

> ```
> ตัวอย่างแสดงการดึงส่วน Summary Zoom Section โดยใช้ดัชนี:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>      int layout = zoomFrame.getLayout();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**ส่งคืน:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```

ดึง [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) สำหรับอ็อบเจ็กต์ Summary Zoom Frame.

--------------------

> ```
> ตัวอย่างแสดงการดึงส่วน Summary Zoom Section โดยใช้ดัชนี:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>      ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**ส่งคืน:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)