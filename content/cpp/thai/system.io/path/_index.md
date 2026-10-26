---
title: Path
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ให้เมธอดสำหรับการจัดการเส้นทาง. นี้เป็นประเภทแบบสถิติโดยไม่มีบริการของอินสแตนซ์. คุณไม่ควรสร้างอินสแตนซ์ของมันด้วยวิธีใด ๆ.
type: docs
weight: 339
url: /th/system.io/path/
---
## Path คลาส

ให้เมธอดสำหรับการจัดการเส้นทาง นี้เป็นประเภทแบบสถิติโดยไม่มีบริการของอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันด้วยวิธีใด ๆ

```cpp
class Path
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| static [String](../../system/string/) [ChangeExtension](./changeextension/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | เปลี่ยนส่วนต่อท้ายในเส้นทางไฟล์ที่ระบุ |
| static void [CheckPath](./checkpath/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | ตรวจสอบว่าเส้นทางที่ระบุเป็นค่าที่ถูกต้องหรือไม่โดยตรวจสอบว่ามีอักขระที่ไม่ถูกต้อง หากพบอักขระที่ไม่ถูกต้องจะเกิดข้อยกเว้น |
| static [String](../../system/string/) [Combine](./combine/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | รวมส่วนเส้นทางที่ระบุเป็นเส้นทางเดียวโดยแทรกอักขระคั่นไดเรกทอรีระหว่างส่วนต่าง ๆ หากจำเป็น |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | รวมสองส่วนเส้นทางที่ระบุเป็นเส้นทางเดียวโดยแทรกอักขระคั่นไดเรกทอรีระหว่างส่วนหากจำเป็น |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | รวมสามส่วนเส้นทางที่ระบุเป็นเส้นทางเดียวโดยแทรกอักขระคั่นไดเรกทอรีระหว่างส่วนหากจำเป็น |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | รวมสี่ส่วนเส้นทางที่ระบุเป็นเส้นทางเดียวโดยแทรกอักขระคั่นไดเรกทอรีระหว่างส่วนหากจำเป็น |
| static [String](../../system/string/) [GetDirectoryName](./getdirectoryname/)(const [String](../../system/string/)\&) | คืนชื่อของไดเรกทอรีที่อ้างอิงโดยเส้นทางที่ระบุ |
| static [String](../../system/string/) [GetExtension](./getextension/)(const [String](../../system/string/)\&) | คืนส่วนต่อท้ายของไฟล์ที่อ้างอิงโดยเส้นทางที่ระบุ |
| static [String](../../system/string/) [GetFileName](./getfilename/)(const [String](../../system/string/)\&) | คืนชื่อของไฟล์ที่อ้างอิงโดยเส้นทางที่ระบุ |
| static [String](../../system/string/) [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const [String](../../system/string/)\&) | คืนชื่อของไฟล์โดยไม่มีส่วนต่อท้ายที่อ้างอิงโดยเส้นทางที่ระบุ |
| static [String](../../system/string/) [GetFullPath](./getfullpath/)(const [String](../../system/string/)\&) | แปลงเส้นทางที่ระบุเป็นเส้นทางสมบูรณ์ |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | คืนอาเรย์ที่บรรจุอักขระที่ไม่อนุญาตในชื่อไฟล์ |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidPathChars](./getinvalidpathchars/)() | คืนอาเรย์ที่บรรจุอักขระที่ไม่อนุญาตในชื่อเส้นทาง |
| static [String](../../system/string/) [GetPathRoot](./getpathroot/)(const [String](../../system/string/)\&) | คืนไดเรกทอรีรากของเส้นทางที่ระบุ |
| static [String](../../system/string/) [GetRandomFileName](./getrandomfilename/)() | คืนชื่อไฟล์ที่สร้างแบบสุ่ม |
| static [String](../../system/string/) [GetTempFileName_](./gettempfilename_/)() | สร้างไฟล์ใหม่ด้วยชื่อที่ไม่ซ้ำและคืนเส้นทางเต็มไปยังไฟล์นั้น |
| static [String](../../system/string/) [GetTempFileNameSafe](./gettempfilenamesafe/)() | สร้างไฟล์ใหม่ด้วยชื่อที่ไม่ซ้ำและคืนเส้นทางเต็มไปยังไฟล์นั้น เป็นคำพ้องของเมธอด [GetTempFileName_()](./gettempfilename_/) |
| static [String](../../system/string/) [GetTempPath](./gettemppath/)() | คืนเส้นทางของไดเรกทอรีชั่วคราวของผู้ใช้ปัจจุบัน |
| static **bool** [HasExtension](./hasextension/)(const [String](../../system/string/)\&) | ตรวจสอบว่าเส้นทางที่ระบุอ้างอิงถึงไฟล์ที่มีส่วนต่อท้ายหรือไม่ |
| static **bool** [IsPathRooted](./ispathrooted/)(const [String](../../system/string/)\&) | ตรวจสอบว่าเส้นทางที่ระบุมีราก (root) หรือไม่ |
| static [String](../../system/string/) [NormalizePath](./normalizepath/)(const [String](../../system/string/)\&) | ทำให้เส้นทางที่ระบุเป็นรูปแบบมาตรฐาน |
| static boost::filesystem::path [ToBoost](./toboost/)(const [String](../../system/string/)\&) | คืนอินสแตนซ์ของคลาส boost::filesystem::path ที่แทนเส้นทางที่ระบุ |
| static [String](../../system/string/) [ToString](./tostring/)(const boost::filesystem::path\&) | คืนการแสดงผลเป็นสตริงของออบเจ็กต์ path ของ Boost ที่ระบุ |
## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | อักขระทางเลือกที่ใช้แยกระดับไดเรกทอรีในเส้นทาง |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | อักขระที่ใช้แยกระดับไดเรกทอรีในเส้นทาง |
| static [PathSeparator](./pathseparator/) | อักขระคั่นที่ใช้แยกสตริงเส้นทางในตัวแปรสภาพแวดล้อม |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | อักขระคั่นของโวลุ่ม |
## หมายเหตุ



```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // สร้างชื่อไฟล์แบบสุ่ม.
  auto filename = Path::GetRandomFileName();

  // พิมพ์ข้อมูลเกี่ยวกับชื่อไฟล์.
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
ตัวอย่างโค้ดนี้แสดงผลลัพธ์ต่อไปนี้:
Filename: qhuzkyqv.y6p
Filename w/o an extension: qhuzkyqv
Extension: .y6p
*/
```

## ดูเพิ่มเติม

* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)