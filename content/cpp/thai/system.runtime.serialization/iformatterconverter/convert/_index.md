---
title: Convert()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ข้อมูล RTTI.
type: docs
weight: 1
url: /th/system.runtime.serialization/iformatterconverter/convert/
---
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) วิธีการ

RTTI information.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | อ็อบเจกต์ที่ต้องแปลง. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | [System::TypeInfo](../../../system/typeinfo/) ที่ค่าจะต้องถูกแปลงเป็น. |

### ค่าที่ส่งคืน

ค่าที่แปลงแล้ว.

## หมายเหตุ

แปลงค่าหนึ่งเป็น [System::TypeInfo](../../../system/typeinfo/) ที่กำหนด. 

## IFormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) วิธีการ

แปลงค่าหนึ่งเป็น [System::TypeCode](../../../system/typecode/) ที่กำหนด.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | อ็อบเจกต์ที่ต้องแปลง. |
| typeCode | [TypeCode](../../../system/typecode/) | [System::TypeCode](../../../system/typecode/) ที่ค่าจะต้องถูกแปลงเป็น. |

### ค่าที่ส่งคืน

ค่าที่แปลงแล้ว.

## ดูเพิ่มเติม

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IFormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)