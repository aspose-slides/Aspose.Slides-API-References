---
title: FileVersionInfo
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "ให้ข้อมูลเกี่ยวกับเวอร์ชันของไฟล์. วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะทำงานและ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อคลาสนี้ด้วยตัวชี้ System::SmartPtr และใช้ตัวชี้นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 1
url: /th/system.diagnostics/fileversioninfo/
---
## FileVersionInfo คลาส

ให้ข้อมูลเกี่ยวกับเวอร์ชันของไฟล์. วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะทำงานและ/หรือข้อข้อผิดพลาดการตรวจสอบ. ควรห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class FileVersionInfo
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [String](../../system/string/) [get_ProductVersion](./get_productversion/)() const | รับค่าเขตข้อมูลเวอร์ชันของผลิตภัณฑ์. |
| static [SharedPtr](../../system/sharedptr/)\<[System::Diagnostics::FileVersionInfo](./)\> [GetVersionInfo](./getversioninfo/)(const [String](../../system/string/)\&) | รับข้อมูลเวอร์ชันไฟล์; ยังไม่ได้ดำเนินการ. |
## ดูเพิ่มเติม

* เนมสเปซ [System::Diagnostics](../)
* ไลบรารี [Aspose.Slides](../../)