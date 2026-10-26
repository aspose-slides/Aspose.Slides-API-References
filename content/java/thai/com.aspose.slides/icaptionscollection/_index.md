---
title: ICaptionsCollection
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงคอลเลกชันของคำบรรยายปิด
type: docs
url: /th/com.aspose.slides/icaptionscollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

แสดงถึงคอลเล็กชันของคำบรรยายปิด
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนค่าคำบรรยายปิดที่ตำแหน่งที่ระบุ |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | เพิ่มคำบรรยายปิดแบบ WebVTT ที่ส่วนท้ายของคอลเล็กชัน |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | เพิ่มคำบรรยายปิดแบบ WebVTT ที่ส่วนท้ายของคอลเล็กชันจากสตรีม |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | ลบคำบรรยายปิดที่ระบุออกจากคอลเล็กชัน |
| [removeAt(int index)](#removeAt-int-) | ลบคำบรรยายปิดที่ตำแหน่งที่ระบุ |
| [clear()](#clear--) | ลบคำบรรยายปิดทั้งหมดออกจากคอลเล็กชัน |
| [getCount()](#getCount--) | คืนค่าจำนวนขององค์ประกอบในคอลเล็กชัน |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```


คืนค่าคำบรรยายปิดที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [ICaptions](../../com.aspose.slides/icaptions).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public abstract ICaptions add(String label, String filePath)
```


เพิ่มคำบรรยายปิดแบบ WebVTT ที่ส่วนท้ายของคอลเล็กชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| label | java.lang.String | ป้ายกำกับของคำบรรยายปิด |
| filePath | java.lang.String | เส้นทางไปยังไฟล์ WebVTT |

**คืนค่า:**
[ICaptions](../../com.aspose.slides/icaptions) - อินสแตนซ์ [ICaptions](../../com.aspose.slides/icaptions) ที่เพิ่มแล้ว
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```


เพิ่มคำบรรยายปิดแบบ WebVTT ที่ส่วนท้ายของคอลเล็กชันจากสตรีม

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| label | java.lang.String | ป้ายกำกับของคำบรรยายปิด |
| stream | java.io.InputStream | สตรีมอินพุตที่มีข้อมูลในรูปแบบ WebVTT |

**คืนค่า:**
[ICaptions](../../com.aspose.slides/icaptions) - อินสแตนซ์ [ICaptions](../../com.aspose.slides/icaptions) ที่เพิ่มแล้ว
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```


ลบคำบรรยายปิดที่ระบุออกจากคอลเล็กชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | คำบรรยายปิดที่ต้องการลบ |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


ลบคำบรรยายปิดที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งของคำบรรยายปิดที่ต้องการลบ |
### clear() {#clear--}
```
public abstract void clear()
```


ลบคำบรรยายปิดทั้งหมดออกจากคอลเล็กชัน
### getCount() {#getCount--}
```
public abstract int getCount()
```


คืนค่าจำนวนขององค์ประกอบในคอลเล็กชัน. อ่านอย่างเดียว  int .

**คืนค่า:**
int