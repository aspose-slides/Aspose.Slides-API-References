---
title: ICustomXmlPartCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวแทนของคอลเลกชันของส่วน XML แบบกำหนดเอง.
type: docs
url: /th/com.aspose.slides/icustomxmlpartcollection/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

เป็นตัวแทนของคอลเลกชันของส่วน XML แบบกำหนดเอง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนองค์ประกอบที่ตำแหน่งที่กำหนด |
| [add(byte[] xmlData)](#add-byte---) | เพิ่มส่วน XML แบบกำหนดเองใหม่ |
| [add(String xmlString)](#add-java.lang.String-) | เพิ่มส่วน XML แบบกำหนดเองใหม่ |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | เพิ่มส่วน XML แบบกำหนดเองใหม่ |
| [removeAt(int index)](#removeAt-int-) | ลบส่วน XML แบบกำหนดเองที่ตำแหน่งที่กำหนด |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | ลบการเกิดขึ้นแรกของอ็อบเจกต์เฉพาะจากคอลเลกชัน |
| [clear()](#clear--) | ลบทุกรายการจากคอลเลกชัน |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```

ส่งคืนองค์ประกอบที่ตำแหน่งที่กำหนด

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ขององค์ประกอบที่จะรับ |

**ค่าที่ส่งกลับ:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - องค์ประกอบที่ตำแหน่งที่กำหนด
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```

เพิ่มส่วน XML แบบกำหนดเองใหม่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xmlData | byte[] | ข้อมูล XML ของส่วนใหม่ที่จะเพิ่ม |

**ค่าที่ส่งกลับ:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - ส่วน XML แบบกำหนดเองที่สร้างขึ้น
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```

เพิ่มส่วน XML แบบกำหนดเองใหม่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xmlString | java.lang.String | สตริง XML ของส่วนใหม่ที่จะเพิ่ม |

**ค่าที่ส่งกลับ:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - ส่วน XML แบบกำหนดเองที่สร้างขึ้น
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```

เพิ่มส่วน XML แบบกำหนดเองใหม่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| inputStream | java.io.InputStream | InputStream ที่มีข้อมูล XML ของส่วนใหม่ที่จะเพิ่ม |

**ค่าที่ส่งกลับ:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - ส่วน XML แบบกำหนดเองที่สร้างขึ้น
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบส่วน XML แบบกำหนดเองที่ตำแหน่งที่กำหนด

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ขององค์ประกอบที่จะลบ |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```

ลบการเกิดขึ้นแรกของอ็อบเจกต์เฉพาะจากคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | ส่วน XML แบบกำหนดเองที่จะลบ |

**ค่าที่ส่งกลับ:**
boolean - true หากรายการถูกลบสำเร็จ; มิฉะนั้น false.
### clear() {#clear--}
```
public abstract void clear()
```

ลบทุกรายการจากคอลเลกชัน