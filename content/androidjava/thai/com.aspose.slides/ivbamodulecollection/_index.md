---
title: IVbaModuleCollection
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นตัวแทนของคอลเลกชันของโมดูล VBA Project.
type: docs
url: /th/com.aspose.slides/ivbamodulecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

เป็นตัวแทนของคอลเลกชันของโมดูล VBA Project.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | รับอิลเมนต์ที่ตำแหน่งที่ระบุ |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | เพิ่มโมดูลเปล่าใหม่ไปยัง VBA Project |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | ลบการเกิดครั้งแรกของอ็อบเจกต์ที่ระบุออกจากคอลเลกชัน |

### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```

รับอิลเมนต์ที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IVbaModule](../../com.aspose.slides/ivbamodule)

### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```

เพิ่มโมดูลเปล่าใหม่ไปยัง VBA Project

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของโมดูล |

**ผลลัพธ์:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - โมดูลที่เพิ่ม

### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```

ลบการเกิดครั้งแรกของอ็อบเจกต์ที่ระบุออกจากคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | โมดูลที่จะลบออกจากคอลเลกชัน |