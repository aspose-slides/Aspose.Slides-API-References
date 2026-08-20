---
title: ICustomXmlPartCollection
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นตัวแทนของคอลเลกชันของส่วน xml ที่กำหนดเอง.
type: docs
url: /th/com.aspose.slides/icustomxmlpartcollection/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

เป็นตัวแทนของคอลเลกชันของส่วน xml ที่กำหนดเอง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนค่าองค์ประกอบที่ตำแหน่ง index ที่ระบุ. |
| [add(byte[] xmlData)](#add-byte---) | เพิ่มส่วน xml กำหนดเองใหม่. |
| [add(String xmlString)](#add-java.lang.String-) | เพิ่มส่วน xml กำหนดเองใหม่. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | เพิ่มส่วน xml กำหนดเองใหม่. |
| [removeAt(int index)](#removeAt-int-) | ลบส่วน xml กำหนดเองที่ตำแหน่ง index ที่ระบุ. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | ลบวัตถุที่เจอครั้งแรกจากคอลเลกชัน. |
| [clear()](#clear--) | ลบรายการทั้งหมดจากคอลเลกชัน. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```


คืนค่าองค์ประกอบที่ตำแหน่ง index ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งดัชนีเริ่มที่ศูนย์ขององค์ประกอบที่ต้องการรับ. |

**ผลลัพธ์:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - องค์ประกอบที่ตำแหน่ง index ที่ระบุ.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```


เพิ่มส่วน xml กำหนดเองใหม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xmlData | byte[] | ข้อมูล xml ของส่วนใหม่ที่ต้องการเพิ่ม. |

**ผลลัพธ์:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - ส่วน xml กำหนดเองที่สร้างขึ้น.
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```


เพิ่มส่วน xml กำหนดเองใหม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xmlString | java.lang.String | สตริง xml ของส่วนใหม่ที่ต้องการเพิ่ม. |

**ผลลัพธ์:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - ส่วน xml กำหนดเองที่สร้างขึ้น.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```


เพิ่มส่วน xml กำหนดเองใหม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| inputStream | java.io.InputStream | inputStream ที่มีข้อมูล xml ของส่วนใหม่ที่ต้องการเพิ่ม. |

**ผลลัพธ์:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - ส่วน xml กำหนดเองที่สร้างขึ้น.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


ลบส่วน xml กำหนดเองที่ตำแหน่ง index ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งดัชนีเริ่มที่ศูนย์ขององค์ประกอบที่ต้องการลบ. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```


ลบวัตถุที่เจอครั้งแรกจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | ส่วน xml กำหนดเองที่ต้องการลบ. |

**ผลลัพธ์:**
boolean - true หาก item ถูกลบสำเร็จ; มิฉะนั้น false.
### clear() {#clear--}
```
public abstract void clear()
```


ลบรายการทั้งหมดจากคอลเลกชัน.