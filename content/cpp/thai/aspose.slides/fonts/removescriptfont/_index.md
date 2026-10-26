---
title: RemoveScriptFont()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ลบการตั้งค่าแบบอักษรที่เชื่อมโยงกับแท็กสคริปต์เฉพาะออกจากคอลเลกชันแบบอักษรของธีม
type: docs
weight: 118
url: /th/aspose.slides/fonts/removescriptfont/
---
## Fonts::RemoveScriptFont(System::String) เมธอด

ลบการตั้งค่าแบบอักษรที่เชื่อมโยงกับแท็กสคริปต์เฉพาะออกจากคอลเลกชันแบบอักษรของธีม

```cpp
void Aspose::Slides::Fonts::RemoveScriptFont(System::String script) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | รหัสสคริปต์ BCP-47 ที่การตั้งค่าแบบอักษรควรถูกลบออก |
## หมายเหตุ

ตัวอย่างนี้แสดงวิธีลบการแมปแบบอักษรสำหรับสคริปต์ฮีบรู:
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [Fonts](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)