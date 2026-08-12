---
title: GetValue()
second_title: Aspose.Slides สำหรับ API ของ C++
description: ดึงค่าคุณสมบัติโดยจากวัตถุที่ระบุ
type: docs
weight: 1
url: /th/system.reflection/propertyinfo/getvalue/
---
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>) เมธอด

รับค่าคุณสมบัติโดยจากวัตถุที่ระบุ

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) เพื่ออ่านคุณสมบัติจาก |

### ค่าที่ส่งคืน

ค่าของคุณสมบัติที่ระบุสำหรับวัตถุที่ระบุ

## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) เมธอด

รับค่าคุณสมบัติโดยจากวัตถุที่ระบุ

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) เพื่ออ่านคุณสมบัติจาก |
| indexer | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | เหล่านี้เป็นค่าดัชนีแบบเลือกสำหรับคุณสมบัติที่มีดัชนี สำหรับคุณสมบัติที่ไม่มีดัชนี ค่านี้ควรเป็น null |

### ค่าที่ส่งคืน

ค่าของคุณสมบัติที่ระบุสำหรับวัตถุที่ระบุ

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [Object](../../../system/object/)
* คลาส [PropertyInfo](../)
* เนมสเปซ [System::Reflection](../../)
* ไลบรารี [Aspose.Slides](../../../)