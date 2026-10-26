---
title: Convert()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "แปลงค่าหนึ่งเป็น System::TypeInfo ที่กำหนด."
type: docs
weight: 1
url: /th/system.runtime.serialization/formatterconverter/convert/
---
## FormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) เมธอด

แปลงค่าหนึ่งเป็น [System::TypeInfo](../../../system/typeinfo/) ที่กำหนด.

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | อ็อบเจกต์ที่จะถูกแปลง. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | [System::TypeInfo](../../../system/typeinfo/) ที่ค่าจะถูกแปลงเป็น. |

### ค่าที่คืน

ค่าที่แปลงแล้ว.

## FormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) เมธอด

แปลงค่าหนึ่งเป็น [System::TypeCode](../../../system/typecode/) ที่กำหนด.

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | อ็อบเจกต์ที่จะถูกแปลง. |
| typeCode | [TypeCode](../../../system/typecode/) | [System::TypeCode](../../../system/typecode/) ที่ค่าจะถูกแปลงเป็น. |

### ค่าที่คืน

ค่าที่แปลงแล้ว.

## ดูเพิ่มเติม

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [FormatterConverter](../)
* เนมสเปซ [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)