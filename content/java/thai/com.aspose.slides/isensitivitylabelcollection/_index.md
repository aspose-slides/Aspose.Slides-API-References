---
title: ISensitivityLabelCollection
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงคอลเลกชันของ sensitivity labels ที่ใช้กับเอกสาร.
type: docs
url: /th/com.aspose.slides/isensitivitylabelcollection/
---
**ส่วนต่อประสานที่ใช้งานทั้งหมด:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable  
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

แสดงถึงคอลเลกชันของ sensitivity labels ที่ถูกนำไปใช้กับเอกสาร.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ส่งคืน sensitivity label ตามดัชนี. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | เพิ่ม sensitivity label ที่ตำแหน่งสุดท้ายของคอลเลกชัน. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | เพิ่ม SensitivityLabel ไปยังคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบ sensitivity label ที่ดัชนีที่ระบุ. |
| [clear()](#clear--) | ลบทุกองค์ประกอบจากคอลเลกชัน. |
| [getCount()](#getCount--) | ดึงจำนวนของทุกองค์ประกอบในคอลเลกชัน. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```

ส่งคืน sensitivity label ตามดัชนี. อ่านอย่างเดียว [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

เพิ่ม sensitivity label ที่ตำแหน่งสุดท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| id | java.lang.String | รหัสของ sensitivity label. |
| siteId | java.util.UUID | ตัวระบุไซต์ของ Azure Active Directory (Azure AD). |
| isEnabled | boolean | แฟล็กที่บ่งบอกว่า sensitivity label ถูกเปิดใช้งานหรือไม่. |
| methodType | int | วิธีการกำหนดสำหรับ sensitivity label. |

**คืนค่า:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```

เพิ่ม SensitivityLabel ไปยังคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | อ็อบเจ็กต์ SensitivityLabel ที่จะถูกเพิ่มไปยังคอลเลกชันที่ตำแหน่งสุดท้าย. |

**คืนค่า:**
int - ดัชนีที่ SensitivityLabel ถูกเพิ่มเข้าไป.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบ sensitivity label ที่ดัชนีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของ sensitivity label ที่จะถูกลบ. |
### clear() {#clear--}
```
public abstract void clear()
```

ลบทุกองค์ประกอบจากคอลเลกชัน.
### getCount() {#getCount--}
```
public abstract int getCount()
```

ดึงจำนวนของทุกองค์ประกอบในคอลเลกชัน. อ่านอย่างเดียว  int .

**คืนค่า:**
int