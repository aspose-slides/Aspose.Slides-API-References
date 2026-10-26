---
title: Directory
second_title: Aspose.Slides สำหรับ API Reference ของ C++
description: มีเมธอดสำหรับจัดการไดเรกทอรี นี้เป็นประเภทแบบสแตติกที่ไม่มีบริการอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันด้วยวิธีใด ๆ
type: docs
weight: 235
url: /th/system.io/directory/
---
## คลาส Directory

มีเมธอดสำหรับจัดการไดเรกทอรี นี้เป็นประเภทแบบสแตติกที่ไม่มีบริการอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันด้วยวิธีใด ๆ

```cpp
class Directory
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| static void [CreateDirectory_](./createdirectory_/)(const [String](../../system/string/)\&) | สร้างไดเรกทอรีทั้งหมดในพาธที่ระบุหากยังไม่มีอยู่ |
| static void [Delete](./delete/)(const [String](../../system/string/)\&, **bool**) | ลบไฟล์หรือไดเรกทอรีที่ระบุ ไม่โยนข้อยกเว้น |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | ค้นหาไดเรกทอรีที่ตรงตามเกณฑ์การค้นหาที่ระบุ ไม่ว่าจะในไดเรกทอรีที่กำหนดหรือในโครงสร้างไดเรกทอรีทั้งหมดที่เริ่มจากไดเรกทอรีที่กำหนด |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | ค้นหาไฟล์ที่ตรงตามเกณฑ์การค้นหาที่ระบุ ไม่ว่าจะในไดเรกทอรีที่กำหนดหรือในโครงสร้างไดเรกทอรีทั้งหมดที่เริ่มจากไดเรกทอรีที่กำหนด |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | ค้นหาไฟล์และไดเรกทอรีที่ตรงตามเกณฑ์การค้นหาที่ระบุ ไม่ว่าจะในไดเรกทอรีที่กำหนดหรือในโครงสร้างไดเรกทอรีทั้งหมดที่เริ่มจากไดเรกทอรีที่กำหนด |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | กำหนดว่าพาธที่ระบุอ้างถึงไดเรกทอรีที่มีอยู่หรือไม่ |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | คืนค่าเวลาการสร้างของเอนทิตี้ที่ระบุเป็นเวลาท้องถิ่น |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | คืนค่าเวลาการสร้างของเอนทิตี้ที่ระบุเป็นเวลา UTC |
| static [String](../../system/string/) [GetCurrentDirectory](./getcurrentdirectory/)() | คืนค่าชื่อเต็ม (รวมถึงพาธ) ของไดเรกทอรีปัจจุบัน |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | ค้นหาไดเรกทอรีที่ตรงตามเกณฑ์การค้นหาที่ระบุ ไม่ว่าจะในไดเรกทอรีที่กำหนดหรือในโครงสร้างไดเรกทอรีทั้งหมดที่เริ่มจากไดเรกทอรีที่กำหนด |
| static [String](../../system/string/) [GetDirectoryRoot](./getdirectoryroot/)(const [String](../../system/string/)\&) | คืนค่าไดเรกทอรีรากของพาธที่ระบุ |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | ค้นหาไฟล์ที่ตรงตามเกณฑ์การค้นหาที่ระบุ ไม่ว่าจะในไดเรกทอรีที่กำหนดหรือในโครงสร้างไดเรกทอรีทั้งหมดที่เริ่มจากไดเรกทอรีที่กำหนด |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFileSystemEntries](./getfilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | ค้นหาไฟล์และไดเรกทอรีที่ตรงตามเกณฑ์การค้นหาที่ระบุ ไม่ว่าจะในไดเรกทอรีที่กำหนดหรือในโครงสร้างไดเรกทอรีทั้งหมดที่เริ่มจากไดเรกทอรีที่กำหนด |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | คืนค่าเวลาการเข้าถึงล่าสุดของเอนทิตี้ที่ระบุเป็นเวลาท้องถิ่น |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | คืนค่าเวลาการเข้าถึงล่าสุดของเอนทิตี้ที่ระบุเป็นเวลา UTC |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | คืนค่าเวลาการเขียนล่าสุดของเอนทิตี้ที่ระบุเป็นเวลาท้องถิ่น |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | คืนค่าเวลาการเขียนล่าสุดของเอนทิตี้ที่ระบุเป็นเวลา UTC |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetLogicalDrives](./getlogicaldrives/)() | ยังไม่ได้ทำ |
| static [DirectoryInfoPtr](../../system/directoryinfoptr/) [GetParent](./getparent/)(const [String](../../system/string/)\&) | คืนค่า shared pointer ไปยังอ็อบเจ็กต์ [DirectoryInfo](../directoryinfo/) ที่เป็นตัวแทนของไดเรกทอรีแม่ของเอนทิตี้ที่ระบุ |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | ย้ายเอนทิตี้ที่ระบุไปยังตำแหน่งใหม่ หากเอนทิตี้ที่ย้ายเป็นไดเรกทอรี จะถูกย้ายพร้อมกับเนื้อหาทั้งหมด |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | ตั้งค่าเวลาการสร้างของเอนทิตี้ที่ระบุเป็นเวลาท้องถิ่น |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | ตั้งค่าเวลาการสร้างของเอนทิตี้ที่ระบุเป็นเวลา UTC |
| static void [SetCurrentDirectory](./setcurrentdirectory/)(const [String](../../system/string/)\&) | ตั้งค่าไดเรกทอรีปัจจุบัน |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | ตั้งค่าเวลาการเข้าถึงล่าสุดของเอนทิตี้ที่ระบุเป็นเวลาท้องถิ่น |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | ตั้งค่าเวลาการเข้าถึงล่าสุดของเอนทิตี้ที่ระบุเป็นเวลา UTC |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | ตั้งค่าเวลาการเขียนล่าสุดของเอนทิตี้ที่ระบุเป็นเวลาท้องถิ่น |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | ตั้งค่าเวลาการเขียนล่าสุดของเอนทิตี้ที่ระบุเป็นเวลา UTC |

## ชนิดนิยาม

| ชนิดนิยาม | คำอธิบาย |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | นามแฝงสำหรับ shared pointer ไปยังอ็อบเจ็กต์ IEnumerable ที่ทำการวนซ้ำชุดของอ็อบเจ็กต์ [String](../../system/string/) |

## หมายเหตุ

```cpp
#include "system/io/directory.h"
#include "system/io/path.h"
#include "system/string.h"
#include <iostream>

void PrintMessage(const System::String &path)
{
  std::cout << "Directory '" << path << (System::IO::Directory::Exists(path) ? "' exists." : "' doesn't exist.") << std::endl;
}

int main()
{
  // สร้างสตริงที่มีพาธไปยังไดเรกทอรี.
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // ตรวจสอบว่าไดเรกทอรีมีอยู่หรือไม่.
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // Print the temp directory information.
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
ตัวอย่างโค้ดนี้แสดงผลลัพธ์ต่อไปนี้:
ไดเรกทอรี 'C:\' มีอยู่.
ไดเรกทอรี 'C:\Some directory' ไม่มีอยู่.
ไดเรกทอรี 'C:\Users\lanor\AppData\Local\Temp\' มีอยู่.
เวลาสร้าง: 27.08.2021 14:21:42
เวลาเข้าถึงล่าสุด: 07.10.2021 12:16:41
เวลาเขียนล่าสุด: 07.10.2021 12:16:41
*/
```

## ดูเพิ่มเติม

* เนมสเปซ [System::IO](../)
* ไลบรารี [Aspose.Slides](../../)