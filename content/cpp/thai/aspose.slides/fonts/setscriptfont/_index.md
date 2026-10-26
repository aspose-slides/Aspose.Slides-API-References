---
title: SetScriptFont()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดชื่อแบบอักษรให้กับแท็กสคริปต์เฉพาะ ซึ่งกำหนดวิธีการแสดงผลข้อความของสคริปต์นั้นในงานนำเสนอ
type: docs
weight: 105
url: /th/aspose.slides/fonts/setscriptfont/
---
## Fonts::SetScriptFont(System::String, System::String) เมธอด

กำหนดชื่อแบบอักษรให้กับแท็กสคริปต์เฉพาะ ซึ่งกำหนดวิธีการแสดงผลข้อความของสคริปต์นั้นในงานนำเสนอ.

```cpp
void Aspose::Slides::Fonts::SetScriptFont(System::String script, System::String fontName) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | รหัสสคริปต์ BCP-47 (เช่น "Arab", "Hebr", "Hans") ที่ระบุระบบการเขียน |
| fontName | [System::String](../../../system/string/) | ชื่อแบบอักษรที่จะกำหนดให้กับสคริปต์ที่ระบุ |

## หมายเหตุ

ตัวอย่างนี้แสดงวิธีการตั้งค่าแบบอักษรสำหรับสคริปต์อารบิกเป็น "Segoe UI":
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [Fonts](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)