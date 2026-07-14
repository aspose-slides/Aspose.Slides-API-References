---
title: SensitivityLabelCollection
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงคอลเลกชันของป้ายความอ่อนไหวที่นำไปใช้กับเอกสาร.
type: docs
url: /th/com.aspose.slides/sensitivitylabelcollection/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**ทุกอินเทอร์เฟซที่นำไปใช้:**  
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)  
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

แสดงคอลเลกชันของป้ายความอ่อนไหวที่นำไปใช้กับเอกสาร  
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนป้ายความอ่อนไหวตามดัชนี |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | เพิ่มป้ายความอ่อนไหวที่ส่วนท้ายของคอลเลกชัน |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | เพิ่ม SensitivityLabel ไปยังคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบป้ายความอ่อนไหวที่ตำแหน่งดัชนีที่ระบุ |
| [clear()](#clear--) | ลบทุกองค์ประกอบจากคอลเลกชัน |
| [iterator()](#iterator--) | คืน enumerator ที่วนซ้ำผ่านคอลเลกชัน |
| [getCount()](#getCount--) | คืนจำนวนขององค์ประกอบในคอลเลกชัน |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ |

### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```

คืนป้ายความอ่อนไหวตามดัชนี

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)

### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

เพิ่มป้ายความอ่อนไหวที่ส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| id | java.lang.String | รหัสของป้ายความอ่อนไหว |
| siteId | java.util.UUID | ตัวระบุไซต์ของ Azure Active Directory (Azure AD) |
| isEnabled | boolean | แฟล็กบ่งชี้ว่าป้ายความอ่อนไหวถูกเปิดใช้งานหรือไม่ |
| methodType | int | วิธีการมอบหมายสำหรับป้ายความอ่อนไหว |

**ผลลัพธ์:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)

### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```

เพิ่ม SensitivityLabel ไปยังคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | อ็อบเจกต์ SensitivityLabel ที่จะเพิ่มไปยังส่วนท้ายของคอลเลกชัน |

**ผลลัพธ์:**
int - ดัชนีที่ SensitivityLabel ถูกเพิ่มเข้าไป

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบป้ายความอ่อนไหวที่ตำแหน่งดัชนีที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของป้ายความอ่อนไหวที่ต้องการลบ |

### clear() {#clear--}
```
public final void clear()
```

ลบทุกองค์ประกอบจากคอลเลกชัน

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```

คืน enumerator ที่วนซ้ำผ่านคอลเลกชัน

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - A  System.Collections.Generic.IEnumerator1  ที่สามารถใช้เพื่อวนซ้ำผ่านคอลเลกชัน

### getCount() {#getCount--}
```
public final int getCount()
```

คืนจำนวนขององค์ประกอบในคอลเลกชัน. อ่านอย่างเดียว  int .

**ผลลัพธ์:**
int

### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```

คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | อาร์เรย์เป้าหมาย |
| index | int | ดัชนีเริ่มต้นในอาร์เรย์เป้าหมาย |