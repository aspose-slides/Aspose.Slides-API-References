---
title: OperatingSystem
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: "แสดงถึงระบบปฏิบัติการเฉพาะและให้ข้อมูลเกี่ยวกับมัน. วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือใช้ operator new, เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือการตรวจสอบความผิดพลาด. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กูเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 1171
url: /th/system/operatingsystem/
---
## OperatingSystem คลาส

แสดงถึงระบบปฏิบัติการเฉพาะและให้ข้อมูลเกี่ยวกับมัน. วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือใช้ operator new, เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือการตรวจจับความผิดพลาด. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กูเมนต์ให้กับฟังก์ชัน.

```cpp
class OperatingSystem
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [PlatformID](../platformid/) [get_Platform](./get_platform/)() const | ส่งคืนรหัสแพลตฟอร์มของระบบปฏิบัติการที่วัตถุปัจจุบันแสดงถึง. |
| [String](../string/) [get_ServicePack](./get_servicepack/)() const | ส่งคืนชื่อ service pack ของระบบปฏิบัติการที่วัตถุปัจจุบันแสดงถึง. |
| const [Version](../version/)\& [get_Version](./get_version/)() const | ส่งคืนการอ้างอิงแบบคงที่ไปยังอ็อบเจกต์ [Version](../version/) ที่แสดงถึงเวอร์ชันของระบบปฏิบัติการที่วัตถุปัจจุบันแสดงถึง. |
| [String](../string/) [get_VersionString](./get_versionstring/)() const | ส่งคืนการแสดงผลเป็นสตริงของเวอร์ชันของระบบปฏิบัติการที่วัตถุปัจจุบันแสดงถึง. |
| static **bool** [IsFreeBSD](./isfreebsd/)() | ระบุว่าการทำงานของแอปพลิเคชันปัจจุบันกำลังรันบน FreeBSD หรือไม่. |
| static **bool** [IsLinux](./islinux/)() | ระบุว่าการทำงานของแอปพลิเคชันปัจจุบันกำลังรันบน Linux หรือไม่. |
| static **bool** [IsMacOS](./ismacos/)() | ระบุว่าการทำงานของแอปพลิเคชันปัจจุบันกำลังรันบน MacOS หรือไม่. |
| static **bool** [IsOSPlatform](./isosplatform/)(const [String](../string/)\&) | ระบุว่าการทำงานของแอปพลิเคชันปัจจุบันกำลังรันบนแพลตฟอร์มที่ระบุหรือไม่. |
| static **bool** [IsWindows](./iswindows/)() | ระบุว่าการทำงานของแอปพลิเคชันปัจจุบันกำลังรันบน [Windows](../../system.windows/) หรือไม่. |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&) | สร้างอินสแตนซ์ที่แสดงถึงระบบปฏิบัติการที่ระบุด้วยรหัสแพลตฟอร์มและเวอร์ชันที่เฉพาะเจาะจง. |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&, const [String](../string/)\&) | สร้างอินสแตนซ์ที่แสดงถึงระบบปฏิบัติการที่ระบุด้วยรหัสแพลตฟอร์ม, เวอร์ชันและ service pack ที่เฉพาะเจาะจง. |
| [String](../string/) [ToString](./tostring/)() const | ส่งคืนการแสดงผลเป็นสตริงของเวอร์ชันของระบบปฏิบัติการที่วัตถุปัจจุบันแสดงถึง. |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)