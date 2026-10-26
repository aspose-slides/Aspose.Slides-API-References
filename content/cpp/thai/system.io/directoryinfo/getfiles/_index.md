---
title: GetFiles()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คืนค่าอาร์เรย์ที่มี shared pointers ไปยังอ็อบเจ็กต์ FileInfo ซึ่งเป็นตัวแทนของไดเรกทอรีทั้งหมดที่ตั้งอยู่ในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทน
type: docs
weight: 157
url: /th/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() เมธอด

คืนค่าอาร์เรย์ที่มี shared pointers ไปยังอ็อบเจ็กต์ [FileInfo](../../fileinfo/) ซึ่งเป็นตัวแทนของไดเรกทอรีทั้งหมดที่ตั้งอยู่ในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทน

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## DirectoryInfo::GetFiles(const String\&) เมธอด

ค้นหาไฟล์ที่ตรงตามเกณฑ์การค้นหาที่ระบุในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทน

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | รูปแบบชื่อของไฟล์ที่ต้องการค้นหา |

### ค่าที่ส่งคืน

อาร์เรย์ของ shared pointers ไปยังอ็อบเจ็กต์ [FileInfo](../../fileinfo/) ที่เป็นตัวแทนของไฟล์ที่พบที่ชื่อตรงกับ **searchPattern**

## DirectoryInfo::GetFiles(const String\&, SearchOption) เมธอด

ค้นหาไฟล์ที่ตรงตามเกณฑ์การค้นหาที่ระบุ ไม่ว่าจะในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทน หรือในโครงสร้างไดเรกทอรีทั้งหมดที่รากอยู่ในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทน

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | รูปแบบชื่อของไฟล์ที่ต้องการค้นหา |
| searchOption | [SearchOption](../../searchoption/) | ระบุว่าการค้นหาต้องทำในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทนเท่านั้นหรือในโครงสร้างไดเรกทอรีทั้งหมดที่รากอยู่ในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทน |

### ค่าที่ส่งคืน

อาร์เรย์ของ shared pointers ไปยังอ็อบเจ็กต์ [FileInfo](../../fileinfo/) ที่เป็นตัวแทนของไฟล์ที่พบที่ชื่อตรงกับ **searchPattern**

## ดูเพิ่มเติม

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)