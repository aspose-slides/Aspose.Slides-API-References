---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวแทนของคุณสมบัติการกำหนดเวลาเพื่อพฤติกรรมของเอฟเฟกต์
type: docs
url: /th/com.aspose.slides/ibehaviorpropertycollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

เป็นตัวแทนของคุณสมบัติการกำหนดเวลาเพื่อพฤติกรรมของเอฟเฟกต์
## เมธอด

| Method | Description |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | เพิ่มคุณสมบัติใหม่ลงในคอลเลกชัน |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | กำหนดดัชนีของรายการเฉพาะโดยใช้ค่าคุณสมบัติใน List |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | แทรกคุณสมบัติใหม่ (โดยใช้ค่าคุณสมบัติที่ระบุ) ลงในคอลเลกชันที่ตำแหน่งที่ระบุ |
| [remove(String propertyValue)](#remove-java.lang.String-) | ลบคุณสมบัติที่ระบุจากคอลเลกชัน |
| [contains(String propertyValue)](#contains-java.lang.String-) | กำหนดว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่ |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```

เพิ่มคุณสมตรใหม่ลงในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| propertyValue | java.lang.String | ค่าของคุณสมบัติที่จะเพิ่ม |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```

กำหนดดัชนีของรายการเฉพาะโดยใช้ค่าคุณสมบัติใน List

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| propertyValue | java.lang.String | ค่าของคุณสมบัติ |

**ค่าที่ส่งกลับ:**
int - ดัชนีของคุณสมบัติที่มีค่าที่ระบุ
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```

แทรกคุณสมบัติใหม่ (โดยใช้ค่าคุณสมบัติที่ระบุ) ลงในคอลเลกชันที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งดัชนีที่ต้องการแทรกคุณสมบัติใหม่ |
| propertyValue | java.lang.String | ค่าของคุณสมบัติที่จะเพิ่ม |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```

ลบคุณสมบัติที่ระบุจากคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| propertyValue | java.lang.String | ค่าของคุณสมบัติที่จะลบ |

**ค่าที่ส่งกลับ:**
boolean - true หากลบคุณสมบัติสำเร็จ boolean
### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

กำหนดว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| propertyValue | java.lang.String | ค่าของคุณสมบัติเพื่อค้นหาใน [IGenericCollection](../../com.aspose.slides/igenericcollection) |

**ค่าที่ส่งกลับ:**
boolean - true หากพบ propertyValue ใน [IGenericCollection](../../com.aspose.slides/igenericcollection); มิฉะนั้น false.