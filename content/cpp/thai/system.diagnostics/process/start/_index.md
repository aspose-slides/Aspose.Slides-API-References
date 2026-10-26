---
title: Start()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เริ่มกระบวนการด้วยพารามิเตอร์ที่กำหนดล่วงหน้า.
type: docs
weight: 14
url: /th/system.diagnostics/process/start/
---
## Process::Start() เมธอด


เริ่มกระบวนการด้วยพารามิเตอร์ที่กำหนดล่วงหน้า.

```cpp
bool System::Diagnostics::Process::Start()
```

## Process::Start(const String\&, const String\&) เมธอด


เริ่มกระบวนการด้วยเส้นทางและอาร์กิวเมนต์ที่ระบุ.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const String &filename, const String &arguments=String::Empty)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | [Process](../) พาธ. |
| arguments | const [String](../../../system/string/)\& | [Process](../) พารามิเตอร์. |

### ค่าที่คืนกลับ

[Object](../../../system/object/) ที่แนบกับกระบวนการที่เริ่มใหม่.

## Process::Start(const SharedPtr\<ProcessStartInfo\>\&) เมธอด


เริ่มกระบวนการด้วยเส้นทางและอาร์กิวเมนต์ที่ระบุ.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const SharedPtr<ProcessStartInfo> &start_info)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| start_info | const [SharedPtr](../../../system/sharedptr/)\<[ProcessStartInfo](../../processstartinfo/)\>\& | ข้อมูลเกี่ยวกับกระบวนการที่จะเริ่ม. |

### ค่าที่คืนกลับ

[Object](../../../system/object/) ที่แนบกับกระบวนการที่เริ่มใหม่.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Process](../)
* คลาส [String](../../../system/string/)
* คลาส [ProcessStartInfo](../../processstartinfo/)
* เนมสเปซ [System::Diagnostics](../../)
* ไลบรารี [Aspose.Slides](../../../)