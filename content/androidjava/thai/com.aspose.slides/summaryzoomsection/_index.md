---
title: SummaryZoomSection
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แทนอ็อบเจ็กต์ Summary Zoom Section ในกรอบ Summary Zoom.
type: docs
url: /th/com.aspose.slides/summaryzoomsection/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject), [com.aspose.slides.SectionZoomFrame](../../com.aspose.slides/sectionzoomframe)

**อินเทอร์เฟซที่ Implement ทั้งหมด:**
[com.aspose.slides.ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
```
public class SummaryZoomSection extends SectionZoomFrame implements ISummaryZoomSection
```

แสดงอ็อบเจ็กต์ Summary Zoom Section ในกรอบ Summary Zoom.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getTitle()](#getTitle--) | คืนค่าส่วนหัวข้อความของอ็อบเจ็กต์ Summary Zoom Section. |
| [setTitle(String value)](#setTitle-java.lang.String-) | คืนค่าส่วนหัวข้อความของอ็อบเจ็กต์ Summary Zoom Section. |
| [getDescription()](#getDescription--) | คืนคำอธิบายข้อความของอ็อบเจ็กต Summary Zoom Section. |
| [setDescription(String value)](#setDescription-java.lang.String-) | คืนคำอธิบายข้อความของอ็อบเจ็กต Summary Zoom Section. |
### getTitle() {#getTitle--}
```
public final String getTitle()
```

คืนค่าส่วนหัวข้อความของอ็อบเจ็กต์ Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**คืนค่า:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

คืนค่าส่วนหัวข้อความของอ็อบเจ็กต์ Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```

คืนคำอธิบายข้อความของอ็อบเจ็กต์ Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**คืนค่า:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```

คืนคำอธิบายข้อความของอ็อบเจ็กต์ Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |