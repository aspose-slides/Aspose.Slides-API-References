---
title: CaptionsCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงคอลเลกชันของคำบรรยายปิด.
type: docs
url: /th/com.aspose.slides/captionscollection/
---
**สืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำไว้ทั้งหมด:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

เป็นคอลเลกชันของคำบรรยายปิด.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนคำบรรยายปิดที่ตำแหน่งที่ระบุ. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | เพิ่มคำบรรยายปิดแบบ WebVTT ที่ส่วนท้ายของคอลเลกชัน. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | เพิ่มคำบรรยายปิดแบบ WebVTT ที่ส่วนท้ายของคอลเลกชันจากสตรีม. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | ลบคำบรรยายปิดที่ระบุออกจากคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบคำบรรยายปิดที่ตำแหน่งที่ระบุ. |
| [clear()](#clear--) | ลบคำบรรยายปิดทั้งหมดออกจากคอลเลกชัน. |
| [getCount()](#getCount--) | ส่งคืนจำนวนขององค์ประกอบในคอลเลกชัน. |
| [iterator()](#iterator--) | ส่งคืนอิเทอเรเตอร์ที่วนซ้ำผ่านคอลเลกชัน. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```


ส่งคืนคำบรรยายปิดที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [ICaptions](../../com.aspose.slides/icaptions).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ค่าที่ส่งกลับ:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public final ICaptions add(String label, String filePath)
```


เพิ่มคำบรรยายปิดแบบ WebVTT ที่ส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| label | java.lang.String | ป้ายกำกับของคำบรรยายปิด. |
| filePath | java.lang.String | เส้นทางไปยังไฟล์ WebVTT. |

**ค่าที่ส่งกลับ:**
[ICaptions](../../com.aspose.slides/icaptions) - อินสแตนซ์ [ICaptions](../../com.aspose.slides/icaptions) ที่เพิ่มเข้ามา.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```


เพิ่มคำบรรยายปิดแบบ WebVTT ที่ส่วนท้ายของคอลเลกชันจากสตรีม.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| label | java.lang.String | ป้ายกำกับของคำบรรยายปิด. |
| stream | java.io.InputStream | สตรีมอินพุตที่มีข้อมูลในรูปแบบ WebVTT. |

**ค่าที่ส่งกลับ:**
[ICaptions](../../com.aspose.slides/icaptions) - อินสแตนซ์ [ICaptions](../../com.aspose.slides/icaptions) ที่เพิ่มเข้ามา.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```


ลบคำบรรยายปิดที่ระบุออกจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | คำบรรยายปิดที่ต้องการลบ. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


ลบคำบรรยายปิดที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งของคำบรรยายปิดที่ต้องการลบ. |

### clear() {#clear--}
```
public final void clear()
```


ลบคำบรรยายปิดทั้งหมดออกจากคอลเลกชัน.

### getCount() {#getCount--}
```
public final int getCount()
```


ส่งคืนจำนวนขององค์ประกอบในคอลเลกชัน. อ่านอย่างเดียว  int .

**ค่าที่ส่งกลับ:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```


ส่งคืนอิเทอเรเตอร์ที่วนซ้ำผ่านคอลเลกชัน.

**ค่าที่ส่งกลับ:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - ตัว  System.Collections.Generic.IEnumerator1  ที่สามารถใช้เพื่อวนผ่านคอลเลกชัน.