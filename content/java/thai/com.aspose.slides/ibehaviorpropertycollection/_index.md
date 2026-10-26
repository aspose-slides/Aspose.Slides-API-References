---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: แสดงคุณสมบัติการตั้งเวลาเพื่อพฤติกรรมของเอฟเฟกต์.
type: docs
url: /th/com.aspose.slides/ibehaviorpropertycollection/
---
**ส่วนต่อประสานที่ใช้งานทั้งหมด:**  
com.aspose.ms.System.Collections.Generic.IGenericList  
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

แสดงคุณสมบัติการตั้งเวลาเพื่อพฤติกรรมของเอฟเฟกต์

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | เพิ่มคุณสมบัติใหม่ลงในคอลเลกชัน |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | กำหนดดัชนีของรายการที่มีค่าคุณสมบัติเฉพาะใน List |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | แทรกคุณสมบัติใหม่ (ด้วยค่าคุณสมบัติที่ระบุ) ลงในคอลเลกชันที่ตำแหน่งที่กำหนด |
| [remove(String propertyValue)](#remove-java.lang.String-) | ลบคุณสมบัติที่ระบุออกจากคอลเลกชัน |
| [contains(String propertyValue)](#contains-java.lang.String-) | ตรวจสอบว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่ |

### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```

เพิ่มคุณสมบัติใหม่ลงในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| propertyValue | java.lang.String | ค่าของคุณสมบัติที่ต้องการเพิ่ม |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```

กำหนดดัชนีของรายการที่มีค่าคุณสมบัติเฉพาะใน List

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| propertyValue | java.lang.String | ค่า ของคุณสมบัติ |

**ค่าที่ส่งคืน:**  
int - ดัชนีของคุณสมบัติที่มีค่าตรงกับที่ระบุ

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```

แทรกคุณสมบัติใหม่ (ด้วยค่าคุณสมบัติที่ระบุ) ลงในคอลเลกชันที่ตำแหน่งที่กำหนด

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่ต้องการแทรกคุณสมบัติใหม่ |
| propertyValue | java.lang.String | ค่าของคุณสมบัติที่ต้องการเพิ่ม |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```

ลบคุณสมบัติที่ระบุออกจากคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| propertyValue | java.lang.String | ค่าของคุณสมบัติที่ต้องการลบ |

**ค่าที่ส่งคืน:**  
boolean - true หากลบคุณสมบัติสำเร็จ

### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

ตรวจสอบว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| propertyValue | java.lang.String | ค่าของคุณสมบัติที่ต้องการค้นหาใน [IGenericCollection](../../com.aspose.slides/igenericcollection) |

**ค่าที่ส่งคืน:**  
boolean - true หากพบ propertyValue ใน [IGenericCollection](../../com.aspose.slides/igenericcollection); มิฉะนั้น false