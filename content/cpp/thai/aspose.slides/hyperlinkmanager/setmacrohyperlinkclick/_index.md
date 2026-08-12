---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: ตั้งค่าไฮเปอร์ลิงก์แมโครเมื่อคลิก.
type: docs
weight: 79
url: /th/aspose.slides/hyperlinkmanager/setmacrohyperlinkclick/
---
## HyperlinkManager::SetMacroHyperlinkClick(System::String) เมธอด

ตั้งค่าไฮเปอร์ลิงก์แมโครเมื่อคลิก.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetMacroHyperlinkClick(System::String macroName) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | ชื่อของแมโคร |

### ค่าที่ส่งกลับ

[Hyperlink](../../hyperlink/) object [IHyperlink](../../ihyperlink/)
## หมายเหตุ

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```

## ดูเพิ่มเติม

* การกำหนดประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [IHyperlink](../../ihyperlink/)
* คลาส [String](../../../system/string/)
* คลาส [HyperlinkManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)