---
title: GetUnderlyingType()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: คืนค่า type argument พื้นฐานของ nullable type ที่ระบุ
type: docs
weight: 1
url: /th/system/nullableutils/getunderlyingtype/
---
## NullableUtils::GetUnderlyingType(const System::TypeInfo\&) เมธอด

คืนค่า type argument พื้นฐานของ nullable type ที่ระบุ

```cpp
static const System::TypeInfo & System::NullableUtils::GetUnderlyingType(const System::TypeInfo &nullableType)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| nullableType | const [System::TypeInfo](../../typeinfo/)\& | อ็อบเจ็กต์ System.Type ที่อธิบายประเภท nullable แบบ generic ที่ปิดแล้ว |

### ค่าที่คืน

ประเภท argument ของพารามิเตอร์ nullableType หากพารามิเตอร์ nullableType เป็นประเภท nullable แบบ generic ที่ปิดแล้ว; มิฉะนั้น, null

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../typeinfo/)
* คลาส [NullableUtils](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)