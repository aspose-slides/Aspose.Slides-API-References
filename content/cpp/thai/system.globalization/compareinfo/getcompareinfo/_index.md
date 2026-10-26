---
title: GetCompareInfo()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับ CompareInfo ที่เชื่อมโยงกับวัฒนธรรมที่ระบุและใช้เมธอดการเปรียบเทียบสตริงในแอสเซมบลีที่ระบุ
type: docs
weight: 183
url: /th/system.globalization/compareinfo/getcompareinfo/
---
## CompareInfo::GetCompareInfo(int, const SharedPtr<Reflection::Assembly>&) เมธอด

รับ [CompareInfo](../) ที่เชื่อมโยงกับวัฒนธรรมที่ระบุและใช้เมธอดการเปรียบเทียบสตริงในแอสเซมบลีที่ระบุ

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture, const SharedPtr<Reflection::Assembly> &assembly)
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| culture | int | ตัวระบุวัฒนธรรม (LCID). |
| assembly | const [SharedPtr](../../../system/sharedptr/)<[Reflection::Assembly](../../../system.reflection/assembly/)>& | แอสเซมบลีที่มีเมธอดการเปรียบเทียบสตริง. |

### ค่าที่ส่งกลับ

[CompareInfo](../) อ็อบเจกต์.

## CompareInfo::GetCompareInfo(const String&, const SharedPtr<Reflection::Assembly>&) เมธอด

รับ [CompareInfo](../) ที่เชื่อมโยงกับวัฒนธรรมที่ระบุและใช้เมธอดการเปรียบเทียบสตริงในแอสเซมบลีที่ระบุ

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name, const SharedPtr<Reflection::Assembly> &assembly)
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| name | const [String](../../../system/string/)& | ชื่อวัฒนธรรม. |
| assembly | const [SharedPtr](../../../system/sharedptr/)<[Reflection::Assembly](../../../system.reflection/assembly/)>& | แอสเซมบลีที่มีเมธอดการเปรียบเทียบสตริง. |

### ค่าที่ส่งกลับ

[CompareInfo](../) อ็อบเจกต์.

## CompareInfo::GetCompareInfo(int) เมธอด

รับ [CompareInfo](../) ที่เชื่อมโยงกับวัฒนธรรมที่ระบุ

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture)
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| culture | int | ตัวระบุวัฒนธรรม (LCID). |

### ค่าที่ส่งกลับ

[CompareInfo](../) อ็อบเจกต์.

## CompareInfo::GetCompareInfo(const String&) เมธอด

รับ [CompareInfo](../) ที่เชื่อมโยงกับวัฒนธรรมที่ระบุ

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name)
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| name | const [String](../../../system/string/)& | ชื่อวัฒนธรรม. |

### ค่าที่ส่งกลับ

[CompareInfo](../) อ็อบเจกต์.

## ดูเพิ่มเติม

* Typedef [CompareInfoPtr](../../compareinfoptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Assembly](../../../system.reflection/assembly/)
* คลาส [CompareInfo](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Globalization](../../)
* ไลบรารี [Aspose.Slides](../../../)