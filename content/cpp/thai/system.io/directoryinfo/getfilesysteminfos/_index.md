---
title: GetFileSystemInfos()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คืนค่าอาเรย์ที่ประกอบด้วย shared pointers ไปยังอ็อบเจ็กต์ FileSystemInfo ที่แทนไฟล์และไดเรกทอรีทั้งหมดที่อยู่ในไดเรกทอรีที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน
type: docs
weight: 170
url: /th/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() method

คืนค่าอาเรย์ที่ประกอบด้วย shared pointers ไปยังอ็อบเจ็กต์ [FileSystemInfo](../../filesysteminfo/) ที่แทนไฟล์และไดเรกทอรีทั้งหมดที่อยู่ในไดเรกทอรีที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## DirectoryInfo::GetFileSystemInfos(const String\&) method

ค้นหาไฟล์และไดเรกทอรีที่ตรงกับเกณฑ์การค้นหาที่กำหนดในไดเรกทอรีที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | รูปแบบชื่อของไฟล์และไดเรกทอรีที่ต้องการค้นหา |

### ค่าที่ส่งกลับ

อาเรย์ของ shared pointers ไปยังอ็อบเจ็กต์ [FileSystemInfo](../../filesysteminfo/) ที่แทนไฟล์และไดเรกทอรีที่พบซึ่งชื่อตรงกับ **searchPattern**

## DirectoryInfo::GetFileSystemInfos(const String\&, SearchOption) method

ค้นหาไฟล์และไดเรกทอรีที่ตรงกับเกณฑ์การค้นหาที่กำหนด ไม่ว่าจะในไดเรกทอรีที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน หรือในต้นไม้ไดเรกทอรีทั้งหมดที่มีรากเป็นไดเรกทอรีที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | รูปแบบชื่อของไฟล์และไดเรกทอรีที่ต้องการค้นหา |
| searchOption | [SearchOption](../../searchoption/) | ระบุว่าการค้นหาต้องดำเนินการในไดเรกทอรีที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเท่านั้นหรือในต้นไม้ไดเรกทอรีทั้งหมดที่มีรากเป็นไดเรกทอรีที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |

### ค่าที่ส่งกลับ

อาเรย์ของ shared pointers ไปยังอ็อบเจ็กต์ [FileSystemInfo](../../filesysteminfo/) ที่แทนไฟล์และไดเรกทอรีที่พบซึ่งชื่อตรงกับ **searchPattern**

## ดูเพิ่มเติม

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)