---
title: Environment
second_title: Aspose.Slides for C++ เอกสารอ้างอิง API
description: บริการ Environment. นี่เป็นประเภทแบบสถิตย์ที่ไม่มีบริการของอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันด้วยวิธีใดเลย
type: docs
weight: 1626
url: /th/system/environment/
---
## Environment struct

[Environment](./) services. นี้เป็นประเภทแบบสแตติกที่ไม่มีบริการของอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันโดยวิธีใดก็ได้

```cpp
class Environment
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| static void [Exit](./exit/)(int) | สิ้นสุดกระบวนการปัจจุบันและส่งคืนรหัสออกที่ระบุให้กับระบบปฏิบัติการ |
| static [String](../string/) [ExpandEnvironmentVariables](./expandenvironmentvariables/)(const [String](../string/)\&) | แทนที่ชื่อของตัวแปรสภาพแวดล้อมที่พบในสตริงที่ระบุด้วยค่าของตัวแปรเหล่านั้นและส่งคืนสตริงที่ได้ |
| static void [FailFast](./failfast/)(const [String](../string/)\&) | ยกเลิกกระบวนการปัจจุบัน |
| static [String](../string/) [get_CommandLine](./get_commandline/)() | ส่งคืนบรรทัดคำสั่งที่ใช้เริ่มกระบวนการปัจจุบัน |
| static [String](../string/) [get_CurrentDirectory](./get_currentdirectory/)() | ส่งคืนเส้นทางไปยังไดเรกทอรีทำงานปัจจุบัน |
| static int [get_ExitCode](./get_exitcode/)() | ส่งคืนรหัสออกของกระบวนการปัจจุบัน |
| static **bool** [get_HasShutdownStarted](./get_hasshutdownstarted/)() | ตรวจสอบว่าการปิดระบบกำลังดำเนินการอยู่ ยังไม่ได้ทำ |
| static **bool** [get_Is64BitProcess](./get_is64bitprocess/)() | ส่งคืน true สำหรับไฟล์ปฏิบัติการ/ไลบรารีบนแพลตฟอร์ม 64-bit |
| static [String](../string/) [get_MachineName](./get_machinename/)() | ส่งคืนชื่อ NetBIOS ของคอมพิวเตอร์นี้ |
| static [String](../string/) [get_NewLine](./get_newline/)() | ส่งคืนสตริง newline ที่ตั้งไว้สำหรับสภาพแวดล้อมปัจจุบัน |
| static const [OperatingSystem](../operatingsystem/)\& [get_OSVersion](./get_osversion/)() | ส่งคืนอ็อบเจ็กต์ [OperatingSystem](../operatingsystem/) ที่มีข้อมูลเกี่ยวกับระบบปฏิบัติการปัจจุบัน |
| static int [get_ProcessorCount](./get_processorcount/)() | ส่งคืนจำนวนโปรเซสเซอร์ของเครื่องปัจจุบัน |
| static [String](../string/) [get_StackTrace](./get_stacktrace/)() | ส่งคืนสตริงที่มีข้อมูลการติดตามสแตคปัจจุบัน |
| static [String](../string/) [get_SystemDirectory](./get_systemdirectory/)() | ส่งคืนเส้นทางไปยังไดเรกทอรีระบบ |
| static int [get_TickCount](./get_tickcount/)() | ส่งคืนจำนวนมิลลิวินาทีที่ผ่านไปตั้งแต่ระบบเริ่มทำงาน |
| static [String](../string/) [get_UserDomainName](./get_userdomainname/)() | ส่งคืนชื่อโดเมนเครือข่ายของผู้ใช้ปัจจุบัน |
| static **bool** [get_UserInteractive](./get_userinteractive/)() | ตรวจสอบว่ากระบวนการปัจจุบันกำลังทำงานในโหมดผู้ใช้โต้ตอบหรือไม่ |
| static [String](../string/) [get_UserName](./get_username/)() | ส่งคืนชื่อผู้ใช้ที่กำลังเข้าสู่ระบบบน OS [Windows](../../system.windows/) |
| static [Version](../version/) [get_Version](./get_version/)() | ส่งคืนอ็อบเจ็กต์ [Version](../version/) ที่แสดงข้อมูลเกี่ยวกับเวอร์ชันของ Common Language Runtime เวอร์ชันที่ส่งคืนโดยเมธอดนี้เป็นค่าแบบปลอมและไม่ได้หมายความว่าทุกคลาสในไลบรารีทำงานตามเวอร์ชันที่ส่งคืน |
| static **int64_t** [get_WorkingSet](./get_workingset/)() | ส่งคืนปริมาณหน่วยความจำจริงที่แมพกับคอนเท็กซ์ของกระบวนการ |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetCommandLineArgs](./getcommandlineargs/)() | ส่งคืนอาเรย์ที่มีอาร์กิวเมนต์บรรทัดคำสั่งที่ใช้เริ่มกระบวนการปัจจุบัน |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&) | ส่งคืนค่าของตัวแปรสภาพแวดล้อมที่ระบุซึ่งเชื่อมโยงกับกระบวนการปัจจุบัน |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | ส่งคืนค่าของตัวแปรสภาพแวดล้อมที่ระบุจากตำแหน่งที่ระบุ |
| static [String](../string/) [GetEnvironmentVariableA](./getenvironmentvariablea/)(const [String](../string/)\&) | ส่งคืนค่าของตัวแปรสภาพแวดล้อมที่ระบุซึ่งเชื่อมโยงกับกระบวนการปัจจุบัน |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)() | ส่งคืนพจนานุกรมที่มีชื่อและค่าของตัวแปรสภาพแวดล้อมทั้งหมดที่เชื่อมโยงกับกระบวนการปัจจุบัน |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)([EnvironmentVariableTarget](../environmentvariabletarget/)) | ส่งคืนพจนานุกรมที่มีชื่อและค่าของตัวแปรสภาพแวดล้อมทั้งหมดจากตำแหน่งที่ระบุ |
| static [String](../string/) [GetEnvironmentVariableW](./getenvironmentvariablew/)(const [String](../string/)\&) | ส่งคืนค่าของตัวแปรสภาพแวดล้อมที่ระบุซึ่งเชื่อมโยงกับกระบวนการปัจจุบัน |
| static [String](../string/) [GetFolderPath](./getfolderpath/)([SpecialFolder](./specialfolder/)) | ส่งคืนเส้นทางเต็มที่อ้างอิงถึงโฟลเดอร์ระบบที่ระบุ |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetLogicalDrives](./getlogicaldrives/)() | ส่งคืนอาเรย์ที่มีชื่อของดิสก์ไดรฟ์ลอจิกทั้งหมดบนคอมพิวเตอร์ปัจจุบัน |
| static **bool** [IsWindowsSubsystemForLinux](./iswindowssubsystemforlinux/)() | ส่งคืน true เฉพาะสำหรับ WSL |
| static void [set_CurrentDirectory](./set_currentdirectory/)(const [String](../string/)\&) | ตั้งค่าไดเรกทอรีที่ระบุให้เป็นไดเรกทอรีทำงานปัจจุบัน |
| static void [set_ExitCode](./set_exitcode/)(int) | ตั้งค่าค่าที่ระบุให้เป็นรหัสออกสำหรับกระบวนการปัจจุบัน |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&) | NOT IMPLEMENTED. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | NOT IMPLEMENTED. |

## เอนัม

| Enum | คำอธิบาย |
| --- | --- |
| [SpecialFolder](./specialfolder/) | แสดงโฟลเดอร์พิเศษของระบบ |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)