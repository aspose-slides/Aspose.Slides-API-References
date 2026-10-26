---
title: ICaptionsCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นคอลเลกชันของคำบรรยายปิด.
type: docs
url: /th/com.aspose.slides/icaptionscollection/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

เป็นคอลเลกชันของคำบรรยายปิด.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนค่าคำบรรยายปิดที่ตำแหน่งที่ระบุ. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | เพิ่มคำบรรยายปิดแบบ WebVTT ที่ส่วนท้ายของคอลเลกชัน. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | เพิ่มคำบรรยายปิดแบบ WebVTT ที่ส่วนท้ายของคอลเลกชันจากสตรีม. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | ลบคำบรรยายปิดที่ระบุออกจากคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบคำบรรยายปิดที่ตำแหน่งที่ระบุ. |
| [clear()](#clear--) | ลบคำบรรยายปิดทั้งหมดจากคอลเลกชัน. |
| [getCount()](#getCount--) | คืนค่าจำนวนของอิลเมนต์ในคอลเลกชัน. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```

คืนค่าคำบรรยายปิดที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [ICaptions](../../com.aspose.slides/icaptions).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public abstract ICaptions add(String label, String filePath)
```

เพิ่มคำบรรยายปิดแบบ WebVTT ที่ส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| label | java.lang.String | ป้ายชื่อของคำบรรยายปิด. |
| filePath | java.lang.String | เส้นทางไปยังไฟล์ WebVTT. |

**ผลลัพธ์:**
[ICaptions](../../com.aspose.slides/icaptions) - อินสตานซ์ที่เพิ่ม [ICaptions](../../com.aspose.slides/icaptions) 
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```

เพิ่มคำบรรยายปิดแบบ WebVTT ที่ส่วนท้ายของคอลเลกชันจากสตรีม.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| label | java.lang.String | ป้ายชื่อของคำบรรยายปิด. |
| stream | java.io.InputStream | สตรีมอินพุตที่มีข้อมูลในรูปแบบ WebVTT. |

**ผลลัพธ์:**
[ICaptions](../../com.aspose.slides/icaptions) - อินสตานซ์ที่เพิ่ม [ICaptions](../../com.aspose.slides/icaptions) 
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```

ลบคำบรรยายปิดที่ระบุออกจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | คำบรรยายปิดที่ต้องการลบ. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบคำบรรยายปิดที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งของคำบรรยายปิดที่ต้องการลบ. |

### clear() {#clear--}
```
public abstract void clear()
```

ลบคำบรรยายปิดทั้งหมดจากคอลเลกชัน.

### getCount() {#getCount--}
```
public abstract int getCount()
```

คืนค่าจำนวนของอิลเมนต์ในคอลเลกชัน. อ่านอย่างเดียว int .

**ผลลัพธ์:**
int