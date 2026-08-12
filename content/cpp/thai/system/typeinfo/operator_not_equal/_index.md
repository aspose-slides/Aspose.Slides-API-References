---
title: operator!=()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: กำหนดว่าตัวอ็อบเจ็กต์ TypeInfo ปัจจุบันและที่ระบุไม่เท่ากัน.
type: docs
weight: 456
url: /th/system/typeinfo/operator_not_equal/
---
## TypeInfo::operator!=(const TypeInfo\&) const เมธอด

กำหนดว่าตัวปัจจุบันและอ็อบเจ็กต์ [TypeInfo](../) ที่ระบุไม่เท่ากัน

```cpp
bool System::TypeInfo::operator!=(const TypeInfo &info) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | อ็อบเจ็กต์ [TypeInfo](../) ที่จะเปรียบเทียบกับ |

### ค่าที่ส่งกลับ

true หากแฮชของอ็อบเจ็กต์ไม่เท่ากัน, มิฉะนั้น - false

## TypeInfo::operator!=(std::nullptr_t) const เมธอด

กำหนดว่าตัวอ็อบเจ็กต์ [TypeInfo](../) ปัจจุบันไม่ใช่อ็อบเจ็กต์ null, ซึ่งหมายถึงเป็นตัวแทนของประเภทบางประเภท

```cpp
bool System::TypeInfo::operator!=(std::nullptr_t) const
```

### ค่าที่ส่งกลับ

true หากอ็อบเจ็กต์ [TypeInfo](../) ปัจจุบันไม่ใช่อ็อบเจ็กต์ null, มิฉะนั้น - false

## ดูเพิ่มเติม

* คลาส [TypeInfo](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)