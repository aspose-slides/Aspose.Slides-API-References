---
title: RemoveScriptFont()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ลบการตั้งค่าแบบอักษรที่เชื่อมโยงกับแท็กสคริปต์เฉพาะจากคอลเลกชันแบบอักษรของธีม
type: docs
weight: 118
url: /th/aspose.slides/ifonts/removescriptfont/
---
## IFonts::RemoveScriptFont(System::String) เมธอด

ลบการตั้งค่าแบบอักษรที่เชื่อมโยงกับแท็กสคริปต์เฉพาะจากคอลเลกชันแบบอักษรของธีม

```cpp
virtual void Aspose::Slides::IFonts::RemoveScriptFont(System::String script)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | รหัสสคริปต์ BCP-47 ที่การตั้งค่าแบบอักษรควรถูกลบออก |

## หมายเหตุ

ตัวอย่างนี้สาธิตวิธีการลบการแมปแบบอักษรสำหรับสคริปต์ Hebrew:
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [IFonts](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)