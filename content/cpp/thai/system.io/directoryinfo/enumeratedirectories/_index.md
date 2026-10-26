---
title: EnumerateDirectories()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: ส่งคืนคอลเล็กชันที่สามารถวนซ้ำได้ซึ่งประกอบด้วยไดเรกทอรีทั้งหมดที่อยู่ในไดเรกทอรีที่แสดงโดยอ็อบเจกต์ปัจจุบัน
type: docs
weight: 105
url: /th/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() เมธอด

คืนค่าคอลเล็กชันที่สามารถวนซ้ำได้ซึ่งประกอบด้วยไดเรกทอรีทั้งหมดที่อยู่ในไดเรกทอรีที่แสดงโดยอ็อบเจกต์ปัจจุบัน

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## DirectoryInfo::EnumerateDirectories(const String\&) เมธอด

ค้นหาไดเรกทอรีที่ตรงตามเกณฑ์การค้นหาที่ระบุในไดเรกทอรีที่แสดงโดยอ็อบเจกต์ปัจจุบัน

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | รูปแบบชื่อของไดเรกทอรีที่ต้องการค้นหา |

### ค่าที่ส่งกลับ

คอลเล็กชันที่สามารถวนซ้ำได้ของ shared pointers ไปยังอ็อบเจกต์ [DirectoryInfo](../) ที่แสดงไดเรกทอรีที่พบซึ่งชื่อตรงกับ **searchPattern**

## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) เมธอด

ค้นหาไดเรกทอรีที่ตรงตามเกณฑ์การค้นหาที่ระบุ ไม่ว่าจะอยู่ในไดเรกทอรีที่แสดงโดยอ็อบเจกต์ปัจจุบันหรือในต้นไม้ไดเรกทอรีทั้งหมดที่มีรากเป็นไดเรกทอรีที่แสดงโดยอ็อบเจกต์ปัจจุบัน

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | รูปแบบชื่อของไดเรกทอรีที่ต้องการค้นหา |
| searchOption | [SearchOption](../../searchoption/) | ระบุว่าการค้นหาต้องทำเฉพาะในไดเรกทอรีที่แสดงโดยอ็อบเจกต์ปัจจุบันหรือในต้นไม้ไดเรกทอรีทั้งหมดที่มีรากเป็นไดเรกทอรีที่แสดงโดยอ็อบเจกต์ปัจจุบัน |

### ค่าที่ส่งกลับ

คอลเล็กชันที่สามารถวนซ้ำได้ของ shared pointers ไปยังอ็อบเจกต์ [DirectoryInfo](../) ที่แสดงไดเรกทอรีที่พบซึ่งชื่อตรงกับ **searchPattern**

## ดูเพิ่มเติม

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)