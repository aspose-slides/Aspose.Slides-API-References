---
title: ColorTranslator
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "ทำการแปลสี. อ็อบเจกต์ของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการตรวจสอบความถูกต้องล้มเหลว. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr เสมอและใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 66
url: /th/system.drawing/colortranslator/
---
## ColorTranslator คลาส

ทำการแปลสี. อ็อบเจกต์ของคลาสนี้ควรจะจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบความถูกต้องล้มเหลว. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) เสมอและใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class ColorTranslator
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| static [Color](../color/) [FromHtml](./fromhtml/)(const [System::String](../../system/string/)\&) | แปลงการแทนค่าสี HTML ที่ระบุให้เป็นอ็อบเจกต์ [Color](../color/) ที่เทียบเท่า. |
| static [Color](../color/) [FromWin32](./fromwin32/)(int) | แปลงสี [Windows](../../system.windows/) ที่ระบุให้เป็นอ็อบเจกต์ [Color](../color/) ที่เทียบเท่า. |
| static [String](../../system/string/) [ToHtml](./tohtml/)(const [Color](../color/)\&) | แปลงอ็อบเจกต์ [Color](../color/) ที่ระบุให้เป็นสตริงที่แทนสี HTML ที่เทียบเท่า. |

## ดูเพิ่มเติม

* เนมสเปซ [System::Drawing](../)
* ไลบรารี [Aspose.Slides](../../)