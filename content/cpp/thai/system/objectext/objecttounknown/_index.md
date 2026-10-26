---
title: ObjectToUnknown()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แปลง Object ให้เป็นประเภทที่ไม่ทราบ โดยจัดการทั้งประเภท smart pointer และสถานการณ์ค่าที่บรรจุไว้ในกล่อง.
type: docs
weight: 131
url: /th/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) method


แปลง [Object](../../object/) ให้เป็นประเภทที่ไม่ทราบ โดยจัดการทั้งประเภท smart pointer และสถานการณ์ค่าที่บรรจุไว้ในกล่อง.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทที่จะเปลี่ยน [Object](../../object/) ไปเป็น. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) ที่จะเปลี่ยน. |

### ค่าที่ส่งคืน

ค่าที่ไม่ได้บรรจุหรือพอยเตอร์ที่แปลงแล้ว.

## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) method


แปลง [Object](../../object/) ให้เป็นประเภทที่ไม่ทราบ โดยจัดการทั้งประเภท smart pointer และสถานการณ์ค่าที่บรรจุไว้ในกล่อง.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทที่จะเปลี่ยน [Object](../../object/) ไปเป็น. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) ที่จะเปลี่ยน. |

### ค่าที่ส่งคืน

ค่าที่ไม่ได้บรรจุหรือพอยเตอร์ที่แปลงแล้ว.

## ดูเพิ่มเติม

* คลาส [SmartPtr](../../smartptr/)
* คลาส [Object](../../object/)
* คลาส [ObjectExt](../)
* โครงสร้าง [IsSmartPtr](../../issmartptr/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)