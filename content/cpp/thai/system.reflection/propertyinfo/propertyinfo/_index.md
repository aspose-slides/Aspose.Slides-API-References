---
title: PropertyInfo()
second_title: Aspose.Slides สำหรับอ้างอิง API C++
description: คอนสตรัคเตอร์. สมบัติที่มีเพียง getter แบบ const.
type: docs
weight: 66
url: /th/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) คอนสตรัคเตอร์

คอนสตรัคเตอร์. สมบัติที่มีเพียง getter แบบ const.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| PropertyType | ประเภทของสมบัติ. |
| ClassType | ประเภทของคลาสที่สมบัติเกี่ยวข้อง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อสมบัติ. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | เมธอดเรียกค่า. |

## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) คอนสตรัคเตอร์

คอนสตรัคเตอร์. สมบัติที่มีเพียง getter ไม่ใช่ const.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| PropertyType | ประเภทของสมบัติ. |
| ClassType | ประเภทของคลาสที่สมบัติเกี่ยวข้อง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อสมบัติ. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | เมธอดเรียกค่า. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) คอนสตรัคเตอร์

คอนสตรัคเตอร์.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| PropertyType | ประเภทของสมบัติ. |
| ClassType | ประเภทของคลาสที่สมบัติเกี่ยวข้อง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อสมบัติ. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | เมธอดตั้งค่า. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | เมธอดเรียกค่า. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) คอนสตรัคเตอร์

คอนสตรัคเตอร์. [Nullable](../../../system/nullable/) สมบัติที่มี setter และ getter.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| PropertyType | ประเภทของสมบัติ. |
| ClassType | ประเภทของคลาสที่สมบัติเกี่ยวข้อง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อสมบัติ. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | เมธอดตั้งค่า. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() | เมธอดเรียกค่า. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) คอนสตรัคเตอร์

คอนสตรัคเตอร์. [Nullable](../../../system/nullable/) สมบัติที่มี getter แบบ const เท่านั้น.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| PropertyType | ประเภทของสมบัติ. |
| ClassType | ประเภทของคลาสที่สมบัติเกี่ยวข้อง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อสมบัติ. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | เมธอดตั้งค่า. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() const | เมธอดเรียกค่า. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) คอนสตรัคเตอร์

คอนสตรัคเตอร์. [Object](../../../system/object/) สมบัติที่มีเพียง getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| PropertyType | ประเภทของสมบัติ. |
| ClassType | ประเภทของคลาสที่สมบัติเกี่ยวข้อง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อสมบัติ. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | เมธอดตั้งค่า. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | เมธอดเรียกค่า. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) คอนสตรัคเตอร์

สร้างข้อมูลสมบัติประเภทสตริง.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| ClassType | ประเภทของคลาสที่สมบัติเกี่ยวข้อง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อสมบัติ. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | เมธอดตั้งค่า. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() | เมธอดเรียกค่า. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) คอนสตรัคเตอร์

สร้างข้อมูลสมบัติประเภทสตริงจากคลาสที่มี getter แบบ const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| ClassType | ประเภทของคลาสที่สมบัติเกี่ยวข้อง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อสมบัติ. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | เมธอดตั้งค่า. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() const | เมธอดเรียกค่า. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) คอนสตรัคเตอร์

สร้างข้อมูลสมบัติ [Decimal](../../../system/decimal/).

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| ClassType | ประเภทของคลาสที่สมบัติเกี่ยวข้อง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อสมบัติ. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | เมธอดตั้งค่า. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() | เมธอดเรียกค่า. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) คอนสตรัคเตอร์

สร้างข้อมูลสมบัติ [Decimal](../../../system/decimal/) จากคลาสที่มี getter แบบ const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| ClassType | ประเภทของคลาสที่สมบัติเกี่ยวข้อง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อสมบัติ. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | เมธอดตั้งค่า. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() const | เมธอดเรียกค่า. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) คอนสตรัคเตอร์

สร้างข้อมูลสมบัติบูลีน.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| ClassType | ประเภทของคลาสที่สมบัติเกี่ยวข้อง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อสมบัติ. |
| set_prop_method | void(ClassType::*)(**bool**) | เมธอดตั้งค่า. |
| get_prop_method | **bool**(ClassType::*)() | เมธอดเรียกค่า. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) คอนสตรัคเตอร์

สร้างข้อมูลสมบัติบูลีนจากคลาสที่มี getter แบบ const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| ClassType | ประเภทของคลาสที่สมบัติเกี่ยวข้อง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อสมบัติ. |
| set_prop_method | void(ClassType::*)(**bool**) | เมธอดตั้งค่า. |
| get_prop_method | **bool**(ClassType::*)() const | เมธอดเรียกค่า. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) คอนสตรัคเตอร์

สร้างข้อมูลสมบัติ **int64_t**.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| ClassType | ประเภทของคลาสที่สมบัติเกี่ยวข้อง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อสมบัติ. |
| set_prop_method | void(ClassType::*)(**int64_t**) | เมธอดตั้งค่า. |
| get_prop_method | **int64_t**(ClassType::*)() | เมธอดเรียกค่า. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) คอนสตรัคเตอร์

สร้างข้อมูลสมบัติ **int64_t** จากคลาสที่มี getter แบบ const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| ClassType | ประเภทของคลาสที่สมบัติเกี่ยวข้อง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อสมบัติ. |
| set_prop_method | void(ClassType::*)(**int64_t**) | เมธอดตั้งค่า. |
| get_prop_method | **int64_t**(ClassType::*)() const | เมธอดเรียกค่า. |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Class [Nullable](../../../system/nullable/)
* Class [Decimal](../../../system/decimal/)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)