---
title: operator==()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: ระบุว่าค่าอ็อบเจ็กต์ TypeInfo ปัจจุบันและที่ระบุเท่ากันหรือไม่.
type: docs
weight: 443
url: /th/system/typeinfo/operator_equal_equal/
---
## TypeInfo::operator==(const TypeInfo\&) const เมธอด

ระบุว่าค่าอ็อบเจ็กต์ [TypeInfo](../) ปัจจุบันและที่ระบุเท่ากันหรือไม่.

```cpp
bool System::TypeInfo::operator==(const TypeInfo &info) const
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | อ็อบเจ็กต์ [TypeInfo](../) เพื่อเปรียบเทียบกับ |

### ค่าที่ส่งกลับ

True หากแฮชของอ็อบเจ็กต์เท่ากัน, มิฉะนั้น - false

## TypeInfo::operator==(std::nullptr_t) const เมธอด

ระบุว่าค่าอ็อบเจ็กต์ [TypeInfo](../) ปัจจุบันเป็น null-object หรือไม่, ซึ่งหมายความว่าไม่แสดงถึงประเภทใด.

```cpp
bool System::TypeInfo::operator==(std::nullptr_t) const
```

### ค่าที่ส่งกลับ

True หากค่าอ็อบเจ็กต์ [TypeInfo](../) ปัจจุบันเป็น null-object, มิฉะนั้น - false

## ดูเพิ่มเติม

* คลาส [TypeInfo](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)