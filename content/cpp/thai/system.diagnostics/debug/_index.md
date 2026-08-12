---
title: Debug
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: คอลเลกชันของเมธอดดีบักที่อนุญาตให้ส่งข้อมูลดีบักไปยังผู้ฟังที่ลงทะเบียนทั้งหมด ฟังก์ชันการแสดงผลทำงานเฉพาะใน Debug เท่านั้น นี่เป็นประเภทสแตติกที่ไม่มีบริการอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันโดยวิธีใด ๆ
type: docs
weight: 105
url: /th/system.diagnostics/debug/
---
## โครงสร้าง Debug


คอลเลกชันของเมธอดดีบักที่อนุญาตให้ส่งข้อมูลดีบักไปยังผู้ฟังที่ลงทะเบียนทั้งหมด ฟังก์ชันการแสดงผลทำงานเพียงใน [Debug](./) เท่านั้น นี่เป็นประเภทสแตติกที่ไม่มีบริการอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันโดยวิธีใดๆ

```cpp
class Debug
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| static void [Assert](./assert/)(**bool**) | ตรวจสอบเงื่อนไขและส่งข้อมูลเมื่อเกิดความล้มเหลว |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&) | ตรวจสอบเงื่อนไขและส่งข้อมูลเมื่อเกิดความล้มเหลว |
| static void [Assert](./assert/)(**bool**, const char *) | ตรวจสอบเงื่อนไขและส่งข้อมูลเมื่อเกิดความล้มเหลว |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | ตรวจสอบเงื่อนไขและส่งข้อมูลเมื่อเกิดความล้มเหลว |
| static void [Fail](./fail/)(const [String](../../system/string/)\&) | ส่งข้อความความล้มเหลว |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[TraceListener](../tracelistener/)\>\>\> [get_Listeners](./get_listeners/)() | เข้าถึงรายการผู้ฟังแบบสแตติก |
| static void [Print](./print/)(const [String](../../system/string/)\&) | พิมพ์ข้อความไปยังอินเทอร์เฟซดีบัก |
| static void [Print](./print/)(const [String](../../system/string/)\&, const [System::ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\&) | พิมพ์ข้อความไปยังอินเทอร์เฟซดีบัก |
| static void [Write](./write/)(const [String](../../system/string/)\&) | เขียนสตริงไปยังอินเทอร์เฟซดีบัก |
| static void [Write](./write/)(const char_t *) | เขียนสตริงไปยังอินเทอร์เฟซดีบัก |
| static void [WriteIf](./writeif/)(**bool**, const [System::String](../../system/string/)\&) | เขียนสตริงไปยังอินเทอร์เฟซดีบักหากเงื่อนไขเป็นจริง |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | เขียนบรรทัดไปยังอินเทอร์เฟซดีบัก |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | เขียนบรรทัดไปยังอินเทอร์เฟซดีบัก |
| static void [WriteLine](./writeline/)(const char_t *) | เขียนบรรทัดไปยังอินเทอร์เฟซดีบัก |
| static void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | เขียนบรรทัดไปยังอินเทอร์เฟซดีบัก |
| static void [WriteLineIf](./writelineif/)(**bool**, const [System::String](../../system/string/)\&) | เขียนบรรทัดไปยังอินเทอร์เฟซดีบักหากเงื่อนไขเป็นจริง |
## ดูเพิ่มเติม

* เนมสเปซ [System::Diagnostics](../)
* ไลบรารี [Aspose.Slides](../../)