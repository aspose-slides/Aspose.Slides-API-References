---
title: GetDirectories()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คืนค่าอาร์เรย์ที่มี shared pointers ไปยังอ็อบเจ็กต์ DirectoryInfo ซึ่งแสดงถึงไดเรกทอรีทั้งหมดที่อยู่ในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันแทน
type: docs
weight: 144
url: /th/system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() เมธอด

คืนค่าอาร์เรย์ที่มี shared pointers ไปยังอ็อบเจ็กต์ [DirectoryInfo](../) ที่แสดงถึงไดเรกทอรีทั้งหมดที่อยู่ในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันแทน

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## DirectoryInfo::GetDirectories(const String\&) เมธอด

ค้นหาไดเรกทอรีที่ตรงตามเงื่อนไขการค้นหาที่ระบุในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันแทน

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | รูปแบบชื่อของไดเรกทอรีที่ต้องการค้นหา |

### ค่าที่คืนกลับ

อาร์เรย์ของ shared pointers ไปยังอ็อบเจ็กต์ [DirectoryInfo](../) ที่แสดงถึงไดเรกทอรีที่พบซึ่งชื่อตรงกับ **searchPattern**

## DirectoryInfo::GetDirectories(const String\&, SearchOption) เมธอด

ค้นหาไดเรกทอรีที่ตรงตามเงื่อนไขการค้นหาที่ระบุ ไม่ว่าจะในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันแทนหรือในต้นไม้ไดเรกทอรีทั้งหมดที่มีรากเป็นไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันแทน

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | รูปแบบชื่อของไดเรกทอรีที่ต้องการค้นหา |
| searchOption | [SearchOption](../../searchoption/) | ระบุว่าการค้นหาต้องทำในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันแทนเท่านั้นหรือในต้นไม้ไดเรกทอรีทั้งหมดที่มีรากเป็นไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันแทนหรือไม่ |

### ค่าที่คืนกลับ

อาร์เรย์ของ shared pointers ไปยังอ็อบเจ็กต์ [DirectoryInfo](../) ที่แสดงถึงไดเรกทอรีที่พบซึ่งชื่อตรงกับ **searchPattern**

## ดูเพิ่มเติม

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)