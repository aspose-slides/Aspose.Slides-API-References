---
title: EnumerateFileSystemInfos()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ส่งคืนคอลเลกชันที่วนได้ซึ่งประกอบด้วยไฟล์และไดเรกทอรีทั้งหมดที่อยู่ในไดเรกทอรีที่อธิบายโดยอ็อบเจกต์ปัจจุบัน.
type: docs
weight: 131
url: /th/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() เมธอด

ส่งคืนคอลเลกชันที่วนได้ซึ่งประกอบด้วยไฟล์และไดเรกทอรีทั้งหมดที่อยู่ในไดเรกทอรีที่อธิบายโดยอ็อบเจกต์ปัจจุบัน

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## DirectoryInfo::EnumerateFileSystemInfos(const String\&) เมธอด

ค้นหาไฟล์และไดเรกทอรีที่ตรงกับเงื่อนไขการค้นหาที่ระบุในไดเรกทอรีที่อธิบายโดยอ็อบเจกต์ปัจจุบัน

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```

### Arguments

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | รูปแบบชื่อของไฟล์และไดเรกทอรีที่ต้องการค้นหา |

### Return Value

ค่าที่ส่งกลับ  
คอลเลกชันที่วนได้ของ shared pointers ไปยังอ็อบเจกต์ [FileSystemInfo](../../filesysteminfo/) ที่แสดงไฟล์และไดเรกทอรีที่พบโดยชื่อตรงกับ **searchPattern**

## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) เมธอด

ค้นหาไฟล์และไดเรกทอรีที่ตรงกับเงื่อนไขการค้นหาที่ระบุ ไม่ว่าจะอยู่ในไดเรกทอรีที่อธิบายโดยอ็อบเจกต์ปัจจุบันหรือในต้นไม้ไดเรกทอรีทั้งหมดที่มีรากอยู่ในไดเรกทอรีที่อธิบายโดยอ็อบเจกต์ปัจจุบัน

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### Arguments

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | รูปแบบชื่อของไฟล์และไดเรกทอรีที่ต้องการค้นหา |
| searchOption | [SearchOption](../../searchoption/) | กำหนดว่าการค้นหาจะทำในไดเรกทอรีที่อธิบายโดยอ็อบเจกต์ปัจจุบันเท่านั้นหรือในต้นไม้ไดเรกทอรีทั้งหมดที่มีรากอยู่ในไดเรกทอรีที่อธิบายโดยอ็อบเจกต์ปัจจุบัน |

### Return Value

ค่าที่ส่งกลับ  
คอลเลกชันที่วนได้ของ shared pointers ไปยังอ็อบเจกต์ [FileSystemInfo](../../filesysteminfo/) ที่แสดงไฟล์และไดเรกทอรีที่พบโดยชื่อตรงกับ **searchPattern**

## See Also

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)