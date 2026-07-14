---
title: ISensitivityLabelCollection
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงคอลเลกชันของป้ายความละเอียดที่ใช้กับเอกสาร
type: docs
url: /th/com.aspose.slides/isensitivitylabelcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

แสดงถึงคอลเลกชันของป้ายความละเอียดที่ใช้กับเอกสาร
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนค่าป้ายความละเอียดตามดัชนี |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | เพิ่มป้ายความละเอียดที่ส่วนท้ายของคอลเลกชัน |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | เพิ่ม SensitivityLabel ไปยังคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบป้ายความละเอียดที่ดัชนีที่ระบุ |
| [clear()](#clear--) | ลบทุกองค์ประกอบจากคอลเลกชัน |
| [getCount()](#getCount--) | รับจำนวนของทุกองค์ประกอบในคอลเลกชัน |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```

คืนค่าป้ายความละเอียดตามดัชนี อ่านอย่างเดียว [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

เพิ่มป้ายความละเอียดที่ส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| id | java.lang.String | รหัสของป้ายความละเอียด |
| siteId | java.util.UUID | ตัวระบุไซต์ของ Azure Active Directory (Azure AD) |
| isEnabled | boolean | แฟล็กที่ระบุว่าป้ายความละเอียดถูกเปิดใช้งานหรือไม่ |
| methodType | int | วิธีการมอบหมายสำหรับป้ายความละเอียด |

**ผลลัพธ์:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```

เพิ่ม SensitivityLabel ไปยังคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | วัตถุ SensitivityLabel ที่จะเพิ่มที่ส่วนท้ายของคอลเลกชัน |

**ผลลัพธ์:**
int - ดัชนีที่ SensitivityLabel ถูกเพิ่ม
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบป้ายความละเอียดที่ดัชนีที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของป้ายความละเอียดที่ต้องการลบ |
### clear() {#clear--}
```
public abstract void clear()
```

ลบทุกองค์ประกอบจากคอลเลกชัน
### getCount() {#getCount--}
```
public abstract int getCount()
```

รับจำนวนของทุกองค์ประกอบในคอลเลกชัน อ่านอย่างเดียว  int .

**ผลลัพธ์:**
int