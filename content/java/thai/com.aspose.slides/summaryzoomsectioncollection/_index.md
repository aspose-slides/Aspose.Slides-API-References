---
title: SummaryZoomSectionCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงคอลเลกชันของอ็อบเจ็กต์ Summary Zoom Section.
type: docs
url: /th/com.aspose.slides/summaryzoomsectioncollection/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
```
public final class SummaryZoomSectionCollection extends DomObject<SummaryZoomFrame> implements ISummaryZoomSectionCollection
```

แสดงถึงคอลเลกชันของอ็อบเจ็กต์ Summary Zoom Section objects.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงเอาอิลีเมนต์ที่ตำแหน่งที่ระบุ |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | สร้างอ็อบเจ็กต์ Summary Zoom Section ใหม่และเพิ่มเข้าไปในคอลเลกชัน |
| [size()](#size--) | ดึงจำนวนอิลีเมนต์ที่อยู่ในคอลเลกชันจริง |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | คืนค่าดัชนีของอ็อบเจ็กต์ SummaryZoomSection ที่ระบุ |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | ลบอ็อบเจ็กต์ Summary Zoom Section ออกจากคอลเลกชัน |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | คืนค่าอิลีเมนต์ Summary Zoom Section สำหรับส่วนที่ระบุ |
| [clear()](#clear--) | ลบอ็อบเจ็กต์ SummaryZoomSection ทั้งหมดออกจากคอลเลกชัน |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกคอลเลกชันทั้งหมดไปยังอาร์เรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | คืนค่าแสดงว่าการเข้าถึงคอลเลกชันนั้นเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด) หรือไม่ |
| [getSyncRoot()](#getSyncRoot--) | คืนค่ารากของการซิงโครไนซ์ |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด |
### get_Item(int index) {#get-Item-int-}
```
public final ISummaryZoomSection get_Item(int index)
```


ดึงอิลีเมนต์ที่ตำแหน่งที่ระบุ อ่านอย่างเดียว [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection).

--------------------

> ```
> ตัวอย่างแสดงการดึงอิลีเมนต์ Summary Zoom Section ตามดัชนี:
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


สร้างอ็อบเจ็กต์ Summary Zoom Section ใหม่และเพิ่มเข้าไปในคอลเลกชัน

--------------------

> ```
> ตัวอย่างแสดงการดึงอิลีเมนต์ Summary Zoom Section ตามดัชนี:
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
| section | [ISection](../../com.aspose.slides/isection) | ส่วนสำหรับอ็อบเจ็กต์ Summary Zoom Section ใหม่ [ISection](../../com.aspose.slides/isection)

--------------------

หากมีอิลีเมนต์สำหรับส่วนนี้อยู่ในคอลเลกชันแล้ว อิลีเมนต์ที่มีอยู่จะถูกส่งกลับ. |
**คืนค่า:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - เพิ่ม [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) อิลีเมนต์
### size() {#size--}
```
public final int size()
```


ดึงจำนวนอิลีเมนต์ที่อยู่ในคอลเลกชันจริง อ่านอย่างเดียว int.

**คืนค่า:**
int
### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public final int indexOf(ISummaryZoomSection summaryZoomSection)
```


คืนค่าดัชนีของอ็อบเจ็กต์ SummaryZoomSection ที่ระบุ.

--------------------

> ```
> ตัวอย่างแสดงการดึงอิลีเมนต์ Summary Zoom Section ตามดัชนี:
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
int - ดัชนีของอ็อบเจ็กต์ SummaryZoomSection หรือ -1 หากอ็อบเจ็กต์ SummaryZoomSection ไม่ได้มาจากคอลเลกชันนี้.
### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public final void removeSummaryZoomSection(ISection section)
```


ลบอ็อบเจ็กต์ Summary Zoom Section ออกจากคอลเลกชัน.

--------------------

> ```
> ตัวอย่างแสดงการดึงอิลีเมนต์ Summary Zoom Section ตามดัชนี:
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
| section | [ISection](../../com.aspose.slides/isection) | ส่วนที่ต้องการลบอ็อบเจ็กต์ Summary Zoom Section [ISection](../../com.aspose.slides/isection). |

### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public final ISummaryZoomSection getSummarySection(ISection section)
```


คืนค่าอิลีเมนต์ Summary Zoom Section สำหรับส่วนที่ระบุ.

--------------------

> ```
> ตัวอย่างแสดงการดึงอิลีเมนต์ Summary Zoom Section ตามดัชนี:
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

**คืนค่า:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) หรือ null หากคอลเลกชันไม่มีอิลีเมนต์สำหรับส่วนนั้น.
### clear() {#clear--}
```
public final void clear()
```


ลบอ็อบเจ็กต์ SummaryZoomSection ทั้งหมดออกจากคอลเลกชัน.

--------------------

> ```
> ตัวอย่างแสดงการดึงอิลีเมนต์ Summary Zoom Section ตามดัชนี:
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


คืนค่าแสดงว่าการเข้าถึงคอลเลกชันนั้นเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด) หรือไม่ อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


คืนค่ารากของการซิงโครไนซ์ อ่านอย่างเดียว Object.

**คืนค่า:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISummaryZoomSection> iterator()
```


คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISummaryZoomSection> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISummaryZoomSection> iteratorJava()
```


คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISummaryZoomSection> - An java.util.Iterator for the entire collection.