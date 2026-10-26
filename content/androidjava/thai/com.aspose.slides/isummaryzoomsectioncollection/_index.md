---
title: ISummaryZoomSectionCollection
second_title: Aspose.Slides สำหรับ Android ผ่านเอกสารอ้างอิง API ของ Java
description: แสดงถึงคอลเลกชันของอ็อบเจกต์ Summary Zoom Section.
type: docs
url: /th/com.aspose.slides/isummaryzoomsectioncollection/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface ISummaryZoomSectionCollection extends IGenericCollection<ISummaryZoomSection>
```

เป็นคอลเลกชันของอ็อบเจ็กต์ Summary Zoom Section.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | รับค่าอิลเมนต์ที่ตำแหน่งที่ระบุ |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | สร้างอ็อบเจ็กต์ Summary Zoom Section ใหม่และเพิ่มเข้าไปในคอลเลกชัน |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | คืนค่าอิลเมนต์ Summary Zoom Section สำหรับส่วนที่ระบุ |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | ลบอ็อบเจ็กต์ Summary Zoom Section จากคอลเลกชัน |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | คืนดัชนีของอ็อบเจ็กต์ SummaryZoomSection ที่ระบุ |
| [clear()](#clear--) | ลบอ็อบเจ็กต์ SummaryZoomSection ทั้งหมดออกจากคอลเลกชัน |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISummaryZoomSection get_Item(int index)
```


รับค่าอิลเมนต์ที่ตำแหน่งที่ระบุ อ่านอย่างเดียว [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection).

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
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection addSummaryZoomSection(ISection section)
```


สร้างอ็อบเจ็กต์ Summary Zoom Section ใหม่และเพิ่มเข้าไปในคอลเลกชัน

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
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Section สำหรับอิลเมนต์ Summary Zoom Section ใหม่ [ISection](../../com.aspose.slides/isection)

หากอิลเมนต์สำหรับส่วนนี้มีอยู่แล้วในคอลเลกชัน จะคืนอิลเมนต์ที่มีอยู่ |

**คืนค่า:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - เพิ่มอิลเมนต์ [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection getSummarySection(ISection section)
```


คืนค่าอิลเมนต์ Summary Zoom Section สำหรับส่วนที่ระบุ

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
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Section เพื่อค้นหา [ISection](../../com.aspose.slides/isection) |

**คืนค่า:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) หรือ null หากคอลเลกชันไม่มีอิลเมนต์สำหรับส่วนดังกล่าว
### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract void removeSummaryZoomSection(ISection section)
```


ลบอ็อบเจ็กต์ Summary Zoom Section จากคอลเลกชัน

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
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Section ที่ต้องการลบอิลเมนต์ Summary Zoom Section [ISection](../../com.aspose.slides/isection) |

### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public abstract int indexOf(ISummaryZoomSection summaryZoomSection)
```


คืนดัชนีของอ็อบเจ็กต์ SummaryZoomSection ที่ระบุ

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
| Parameter | Type | Description |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | อ็อบเจ็กต์ SummaryZoomSection ที่ต้องการค้นหา [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) |

**คืนค่า:**
int - ดัชนีของอ็อบเจ็กต์ SummaryZoomSection หรือ -1 หากอ็อบเจ็กต์ไม่ได้อยู่ในคอลเลกชันนี้
### clear() {#clear--}
```
public abstract void clear()
```


ลบอ็อบเจ็กต์ SummaryZoomSection ทั้งหมดออกจากคอลเลกชัน

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