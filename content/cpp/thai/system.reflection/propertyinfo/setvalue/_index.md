---
title: SetValue()
second_title: Aspose.Slides สำหรับ C++ API เอกสารอ้างอิง
description: ตั้งค่าคุณสมบัติให้กับอ็อบเจ็กต์ที่ระบุ
type: docs
weight: 14
url: /th/system.reflection/propertyinfo/setvalue/
---
## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>) เมธอด


ตั้งค่าคุณสมบัติให้กับอ็อบเจ็กต์ที่ระบุ

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) เพื่อเขียนคุณสมบัติ |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | ค่าของคุณสมบัติที่จะตั้งค่า |

## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) เมธอด


ตั้งค่าคุณสมบัติให้กับอ็อบเจ็กต์ที่ระบุ

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) เพื่อเขียนคุณสมบัติ |
| indexer | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | เหล่านี้เป็นค่าอินเด็กซ์ทางเลือกสำหรับคุณสมบัติที่มีอินเด็กซ์. สำหรับคุณสมบัติที่ไม่มีอินเด็กซ์, ค่านี้ควรเป็น null. |
| value | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | ค่าของคุณสมบัติที่จะตั้งค่า. |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)