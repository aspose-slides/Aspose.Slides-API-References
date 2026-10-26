---
title: SetScriptFont()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดชื่อแบบอักษรให้กับแท็กสคริปต์เฉพาะ ซึ่งกำหนดวิธีการแสดงผลข้อความของสคริปต์นั้นในงานนำเสนอ
type: docs
weight: 105
url: /th/aspose.slides/ifonts/setscriptfont/
---
## IFonts::SetScriptFont(System::String, System::String) เมธอด

กำหนดชื่อแบบอักษรให้กับสคริปต์แท็กเฉพาะ ซึ่งกำหนดว่าข้อความของสคริปต์นั้นจะถูกเรนเดอร์ในงานนำเสนออย่างไร

```cpp
virtual void Aspose::Slides::IFonts::SetScriptFont(System::String script, System::String fontName)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | รหัสสคริปต์ BCP-47 (เช่น "Arab", "Hebr", "Hans") ที่ระบุระบบการเขียน |
| fontName | [System::String](../../../system/string/) | ชื่อแบบอักษรที่จะกำหนดให้กับสคริปต์ที่ระบุ |

## หมายเหตุ

ตัวอย่างนี้แสดงวิธีตั้งค่าแบบอักษรสำหรับสคริปต์ภาษาอาหรับเป็น "Segoe UI": 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [IFonts](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)