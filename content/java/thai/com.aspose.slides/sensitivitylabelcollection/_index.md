---
title: SensitivityLabelCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวแทนของคอลเลกชันของป้ายความละเอียดที่ใช้กับเอกสาร.
type: docs
url: /th/com.aspose.slides/sensitivitylabelcollection/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**  
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)  
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

เป็นตัวแทนของคอลเลกชันของป้ายความละเอียดที่ใช้กับเอกสาร

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนป้ายความละเอียดตามดัชนี |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | เพิ่มป้ายความละเอียดที่ส่วนท้ายของคอลเลกชัน |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | เพิ่ม SensitivityLabel ไปยังคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบป้ายความละเอียดที่ตำแหน่งที่ระบุ |
| [clear()](#clear--) | ลบสมาชิกทั้งหมดออกจากคอลเลกชัน |
| [iterator()](#iterator--) | ส่งคืน enumerator ที่ทำการวนซ้ำผ่านคอลเลกชัน |
| [getCount()](#getCount--) | ส่งคืนจำนวนสมาชิกในคอลเลกชัน |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | คัดลอกสมาชิกทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ |

### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```

ส่งคืนป้ายความละเอียดตามดัชนี

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ค่าที่ส่งคืน:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)

### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

เพิ่มป้ายความละเอียดที่ส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| id | java.lang.String | ID ของป้ายความละเอียด |
| siteId | java.util.UUID | ตัวระบุไซต์ของ Azure Active Directory (Azure AD) |
| isEnabled | boolean | ธงแสดงว่าป้ายความละเอียดเปิดใช้งานหรือไม่ |
| methodType | int | วิธีการกำหนดค่าป้ายความละเอียด |

**ค่าที่ส่งคืน:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)

### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
``` 
public final int add(ISensitivityLabel label)
```

เพิ่ม SensitivityLabel ไปยังคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | วัตถุ SensitivityLabel ที่จะเพิ่มที่ส่วนท้ายของคอลเลกชัน |

**ค่าที่ส่งคืน:**
int - ดัชนีที่ SensitivityLabel ถูกเพิ่มเข้าไป

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบป้ายความละเอียดที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของป้ายความละเอียดที่ต้องการลบ |

### clear() {#clear--}
```
public final void clear()
```

ลบสมาชิกทั้งหมดออกจากคอลเลกชัน

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```

ส่งคืน enumerator ที่ทำการวนซ้ำผ่านคอลเลกชัน

**ค่าที่ส่งคืน:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - A  System.Collections.Generic.IEnumerator1  ที่สามารถใช้เพื่อวนซ้ำผ่านคอลเลกชัน

### getCount() {#getCount--}
```
public final int getCount()
```

ส่งคืนจำนวนสมาชิกในคอลเลกชัน อ่านอย่างเดียว  int .

**ค่าที่ส่งคืน:**
int

### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```

คัดลอกสมาชิกทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | อาร์เรย์เป้าหมาย |
| index | int | ดัชนีเริ่มต้นในอาร์เรย์เป้าหมาย |