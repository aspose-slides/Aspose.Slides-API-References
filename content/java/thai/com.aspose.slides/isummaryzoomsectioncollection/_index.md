---
title: ISummaryZoomSectionCollection
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงถึงคอลเลกชันของอ็อบเจกต์ Summary Zoom Section.
type: docs
url: /th/com.aspose.slides/isummaryzoomsectioncollection/
---
**อินเทอร์เฟซที่ทำตามทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface ISummaryZoomSectionCollection extends IGenericCollection<ISummaryZoomSection>
```

แสดงคอลเลกชันของอ็อบเจกต์ Summary Zoom Section.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงเอาอิลีเมนต์ที่ตำแหน่งที่ระบุ |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | สร้างอ็อบเจกต์ Summary Zoom Section ใหม่และเพิ่มเข้าไปในคอลเลกชัน |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | คืนค่าอิลีเมนต์ Summary Zoom Section สำหรับส่วนที่ระบุ |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | ลบอ็อบเจกต์ Summary Zoom Section ออกจากคอลเลกชัน |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | คืนดัชนีของอ็อบเจกต์ SummaryZoomSection ที่กำหนด |
| [clear()](#clear--) | ลบอ็อบเจกต์ SummaryZoomSection ทั้งหมดออกจากคอลเลกชัน |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISummaryZoomSection get_Item(int index)
```


ดึงเอาอิลีเมนต์ที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection).

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection zoomSection = collection.get_Item(1);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ค่าที่คืน:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection addSummaryZoomSection(ISection section)
```


สร้างอ็อบเจกต์ Summary Zoom Section ใหม่และเพิ่มเข้าไปในคอลเลกชัน

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection newZoomSection = collection.addSummaryZoomSection(pres.getSections().get_Item(3));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | ส่วนสำหรับอิลีเมนต์ Summary Zoom Section ใหม่ [ISection](../../com.aspose.slides/isection)

ถ้าอิลีเมนต์สำหรับส่วนนี้มีอยู่แล้วในคอลเลกชัน อิลีเมนต์ที่มีอยู่จะถูกคืนค่า

**ค่าที่คืน:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - เพิ่มอิลีเมนต์ [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) 
### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection getSummarySection(ISection section)
```


คืนค่าอิลีเมนต์ Summary Zoom Section สำหรับส่วนที่ระบุ

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection selectedObject = collection.getSummarySection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | ส่วนที่ต้องการค้นหา [ISection](../../com.aspose.slides/isection) |

**ค่าที่คืน:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) หรือ null หากคอลเลกชันไม่มีอิลีเมนต์สำหรับส่วนนั้น
### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract void removeSummaryZoomSection(ISection section)
```


ลบอ็อบเจกต์ Summary Zoom Section ออกจากคอลเลกชัน

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       collection.removeSummaryZoomSection(pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | ส่วนที่ต้องการลบอิลีเมนต์ Summary Zoom Section [ISection](../../com.aspose.slides/isection). |

### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public abstract int indexOf(ISummaryZoomSection summaryZoomSection)
```


คืนดัชนีของอ็อบเจกต์ SummaryZoomSection ที่กำหนด

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection selectedObject = collection.getSummarySection(pres.getSections().get_Item(2));
>       int idx = collection.indexOf(selectedObject);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | อ็อบเจกต์ SummaryZoomSection ที่ต้องการค้นหา [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection). |

**ค่าที่คืน:**
int - ดัชนีของอ็อบเจกต์ SummaryZoomSection หรือ -1 หากอ็อบเจกต์ SummaryZoomSection ไม่อยู่ในคอลเลกชันนี้
### clear() {#clear--}
```
public abstract void clear()
```


ลบอ็อบเจกต์ SummaryZoomSection ทั้งหมดออกจากคอลเลกชัน

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       collection.clear();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```