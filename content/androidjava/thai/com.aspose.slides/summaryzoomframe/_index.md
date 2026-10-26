---
title: SummaryZoomFrame
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง Java API
description: เป็นอ็อบเจ็กต์ Summary Zoom ในสไลด์
type: docs
url: /th/com.aspose.slides/summaryzoomframe/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

แสดงถึงวัตถุ Summary Zoom ในสไลด์
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getLayout()](#getLayout--) | รับเลเอาต์ของส่วน Summary Zoom ในเฟรม |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | รับ [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) สำหรับวัตถุ Summary Zoom Frame |

### getLayout() {#getLayout--}
```
public final int getLayout()
```

รับเลเอาต์ของส่วน Summary Zoom ในเฟรม ค่าเริ่มต้นคือ GridLayout.

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


**คืนค่า:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```

รับ [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) สำหรับวัตถุ Summary Zoom Frame.

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


**คืนค่า:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)