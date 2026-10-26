---
title: GetScriptFont()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: รับชื่อแบบอักษรที่เชื่อมโยงกับแท็กสคริปต์เฉพาะจากธีมการนำเสนอ
type: docs
weight: 92
url: /th/aspose.slides/fonts/getscriptfont/
---
## Fonts::GetScriptFont(System::String) เมธอด

รับชื่อแบบอักษรที่เชื่อมโยงกับแท็กสคริปต์เฉพาะจากธีมการนำเสนอ.

```cpp
System::String Aspose::Slides::Fonts::GetScriptFont(System::String script) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | รหัสสคริปต์ BCP-47 (เช่น "Latn", "Cyrl", "Jpan") ที่ใช้ระบุระบบการเขียน |

### ค่าที่ส่งกลับ

ชื่อแบบอักษรที่ใช้สำหรับสคริปต์ที่ระบุ, หรือ **null** หากสคริปต์ไม่ได้กำหนด.

## หมายเหตุ

ตัวอย่างนี้แสดงวิธีการดึงแบบอักษรที่กำหนดให้สคริปต์ซีริลลิกในธีมการนำเสนอ. 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [Fonts](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)