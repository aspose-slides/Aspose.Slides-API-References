---
title: EnumerateFiles()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งคืนคอลเลกชันที่สามารถวนซ้ำได้ซึ่งประกอบด้วยไฟล์ทั้งหมดที่อยู่ในไดเรกทอรีที่แทนโดยอ็อบเจกต์ปัจจุบัน
type: docs
weight: 118
url: /th/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() เมธอด


ส่งคืนคอลเลกชันที่สามารถวนซ้ำได้ซึ่งประกอบด้วยไฟล์ทั้งหมดที่อยู่ในไดเรกทอรีที่แทนโดยอ็อบเจกต์ปัจจุบัน

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## DirectoryInfo::EnumerateFiles(const String\&) เมธอด


ค้นหาไฟล์ที่ตรงตามเงื่อนไขการค้นหาที่กำหนดในไดเรกทอรีที่แทนโดยอ็อบเจกต์ปัจจุบัน

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | รูปแบบชื่อของไฟล์ที่ต้องการค้นหา |

### ค่าที่ส่งคืน

คอลเลกชันที่สามารถวนซ้ำได้ของ shared pointers ไปยังวัตถุ [FileInfo](../../fileinfo/) ที่แสดงไฟล์ที่พบซึ่งชื่อตรงกับ **searchPattern**

## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) เมธอด


ค้นหาไฟล์ที่ตรงตามเงื่อนไขการค้นหาที่กำหนด ไม่ว่าจะในไดเรกทอรีที่แทนโดยอ็อบเจกต์ปัจจุบันหรือในต้นไม้ไดเรกทอรีทั้งหมดที่เริ่มจากไดเรกทอรีที่แทนโดยอ็อบเจกต์ปัจจุบัน

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | รูปแบบชื่อของไฟล์ที่ต้องการค้นหา |
| searchOption | [SearchOption](../../searchoption/) | ระบุว่าการค้นหาต้องทำเฉพาะในไดเรกทอรีที่แทนโดยอ็อบเจกต์ปัจจุบันหรือในต้นไม้ไดเรกทอรีทั้งหมดที่เริ่มจากไดเรกทอรีที่แทนโดยอ็อบเจกต์ปัจจุบัน |

### ค่าที่ส่งคืน

คอลเลกชันที่สามารถวนซ้ำได้ของ shared pointers ไปยังวัตถุ [FileInfo](../../fileinfo/) ที่แสดงไฟล์ที่พบซึ่งชื่อตรงกับ **searchPattern**

## ดูเพิ่มเติม

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)