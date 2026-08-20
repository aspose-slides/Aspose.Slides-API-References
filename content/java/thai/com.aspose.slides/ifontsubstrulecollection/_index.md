---
title: IFontSubstRuleCollection
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงคอลเลกชันของการทดแทนแบบอักษร.
type: docs
url: /th/com.aspose.slides/ifontsubstrulecollection/
---
**ส่วนต่อประสานที่ใช้งานทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface IFontSubstRuleCollection extends IGenericCollection<IFontSubstRule>
```

แสดงถึงคอลเลกชันของการทดแทนแบบอักษร.
## เมธอด

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบตามดัชนีที่ระบุ |
| [add(IFontSubstRule value)](#add-com.aspose.slides.IFontSubstRule-) | เพิ่มกฎการทดแทนแบบอักษรใหม่ไปยังคอลเลกชัน |
| [remove(IFontSubstRule value)](#remove-com.aspose.slides.IFontSubstRule-) | ลบการปรากฏครั้งแรกของอ็อบเจกต์ที่ระบุออกจากคอลเลกชัน |

### get_Item(int index) {#get-Item-int-}
```
public abstract IFontSubstRule get_Item(int index)
```

รับองค์ประกอบตามดัชนีที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
### add(IFontSubstRule value) {#add-com.aspose.slides.IFontSubstRule-}
```
public abstract void add(IFontSubstRule value)
```

เพิ่มกฎการทดแทนแบบอักษรใหม่ไปยังคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | กฎการทดแทนแบบอักษร [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |

### remove(IFontSubstRule value) {#remove-com.aspose.slides.IFontSubstRule-}
```
public abstract void remove(IFontSubstRule value)
```

ลบการปรากฏครั้งแรกของอ็อบเจกต์ที่ระบุออกจากคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | โมดูลที่จะลบออกจากคอลเลกชัน |
