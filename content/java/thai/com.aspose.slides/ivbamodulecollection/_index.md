---
title: IVbaModuleCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงคอลเลกชันของโมดูล VBA Project.
type: docs
url: /th/com.aspose.slides/ivbamodulecollection/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

แสดงถึงคอลเลกชันของโมดูล VBA Project.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | รับอิลิเมนต์ที่ตำแหน่งที่ระบุ |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | เพิ่มโมดูลว่างใหม่เข้าไปใน VBA Project |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | ลบการเกิดแรกของอ็อบเจกต์ที่ระบุจากคอลเลกชัน |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```

รับอิลิเมนต์ที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```

เพิ่มโมดูลว่างใหม่เข้าไปใน VBA Project

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของโมดูล |

**ผลลัพธ์:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - โมดูลที่เพิ่ม
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```

ลบการเกิดแรกของอ็อบเจกต์ที่ระบุจากคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | โมดูลที่จะลบออกจากคอลเลกชอน |