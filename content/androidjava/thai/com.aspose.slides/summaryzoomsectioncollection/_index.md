---
title: SummaryZoomSectionCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวแทนของคอลเลกชันของอ็อบเจ็กต์ Summary Zoom Section
type: docs
url: /th/com.aspose.slides/summaryzoomsectioncollection/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่ทำการนำไปใช้ทั้งหมด:**
[com.aspose.slides.ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
```
public final class SummaryZoomSectionCollection extends DomObject<SummaryZoomFrame> implements ISummaryZoomSectionCollection
```

Represents a collection of Summary Zoom Section objects.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงอิลิเมนต์ที่ตำแหน่งที่ระบุ. |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | สร้างอ็อบเจ็กต์ Summary Zoom Section ใหม่และเพิ่มลงในคอลเลกชัน |
| [size()](#size--) | ดึงจำนวนอิลิเมนต์ที่บรรจุอยู่จริงในคอลเลกชัน. |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | ส่งคืนดัชนีของอ็อบเจ็กต์ SummaryZoomSection ที่ระบุ. |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | ลบอ็อบเจ็กต์ Summary Zoom Section ออกจากคอลเลกชัน. |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | ส่งคืนอิลิเมนต์ Summary Zoom Section สำหรับส่วนที่ระบุ. |
| [clear()](#clear--) | ลบอ็อบเจ็กต์ SummaryZoomSection ทั้งหมดออกจากคอลเลกชัน. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกคอลเลกชันทั้งหมดไปยังอาร์เรย์ที่ระบุ. |
| [isSynchronized()](#isSynchronized--) | ส่งคืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันนั้นถูกซิงโครไนซ์ (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | ส่งคืนรากของการซิงโครไนซ์. |
| [iterator()](#iterator--) | ส่งคืน enumerator ที่ทำการวนซ้ำผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด. |

### get_Item(int index) {#get-Item-int-}
```
public final ISummaryZoomSection get_Item(int index)
```

ดึงอิลิเมนต์ที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection).

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

**คืนค่า:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)

### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public final ISummaryZoomSection addSummaryZoomSection(ISection section)
```

สร้างอ็อบเจ็กต์ Summary Zoom Section ใหม่และเพิ่มลงในคอลเลกชัน

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
| section | [ISection](../../com.aspose.slides/isection) | ส่วนสำหรับอิลิเมนต์ Summary Zoom Section ใหม่ [ISection](../../com.aspose.slides/isection)

If an element for this section already exists in the collection, the existing element is returned. |
  
**คืนค่า:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - เพิ่มอิลิเมนต์ [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)

### size() {#size--}
```
public final int size()
```

ดึงจำนวนอิลิเมนต์ที่บรรจุอยู่จริงในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**
int

### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public final int indexOf(ISummaryZoomSection summaryZoomSection)
```

ส่งคืนดัชนีของอ็อบเจ็กต์ SummaryZoomSection ที่ระบุ.

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
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | อ็อบเจ็กต์ SummaryZoomSection ที่จะค้นหา [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection). |

**คืนค่า:**
int - ดัชนีของอ็อบเจ็กต์ SummaryZoomSection หรือ -1 หากอ็อบเจ็กต์ SummaryZoomSection ไม่อยู่ในคอลเลกชันนี้.

### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public final void removeSummaryZoomSection(ISection section)
```

ลบอ็อบเจ็กต์ Summary Zoom Section ออกจากคอลเลกชัน.

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
| section | [ISection](../../com.aspose.slides/isection) | ส่วนที่ต้องการลบอิลิเมนต์ Summary Zoom Section [ISection](../../com.aspose.slides/isection). |

### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public final ISummaryZoomSection getSummarySection(ISection section)
```

ส่งคืนอิลิเมนต์ Summary Zoom Section สำหรับส่วนที่กำหนด.

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
| section | [ISection](../../com.aspose.slides/isection) | ส่วนที่จะค้นหา [ISection](../../com.aspose.slides/isection) |

**คืนค่า:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) หรือ null หากคอลเลกชันไม่มีอิลิเมนต์สำหรับส่วนนี้.

### clear() {#clear--}
```
public final void clear()
```

ลบอ็อบเจ็กต์ SummaryZoomSection ทั้งหมดออกจากคอลเลกชัน.

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

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกคอลเลกชันทั้งหมดไปยังอาร์เรย์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์เป้าหมาย |
| index | int | ดัชนีในอาร์เรย์เป้าหมาย. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

ส่งคืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันนั้นถูกซิงโครไนซ์ (thread-safe). อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ส่งคืนรากของการซิงโครไนซ์. อ่านอย่างเดียว Object.

**คืนค่า:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISummaryZoomSection> iterator()
```

ส่งคืน enumerator ที่ทำการวนซ้ำผ่านคอลเลกชัน.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISummaryZoomSection> - IGenericEnumerator ที่สามารถใช้สำหรับวนซ้ำผ่านคอลเลกชัน

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISummaryZoomSection> iteratorJava()
```

ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISummaryZoomSection> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด