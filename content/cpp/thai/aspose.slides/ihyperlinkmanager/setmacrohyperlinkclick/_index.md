---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ตั้งลิงก์ไฮเปอร์แมโครเมื่อคลิก.
type: docs
weight: 79
url: /th/aspose.slides/ihyperlinkmanager/setmacrohyperlinkclick/
---
## IHyperlinkManager::SetMacroHyperlinkClick(System::String) เมธอด


ตั้งลิงก์ไฮเปอร์แมโครเมื่อคลิก.

```cpp
virtual System::SharedPtr<IHyperlink> Aspose::Slides::IHyperlinkManager::SetMacroHyperlinkClick(System::String macroName)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | ชื่อของแมโคร |

### ค่าที่คืนค่า

[Hyperlink](../../hyperlink/) วัตถุ [IHyperlink](../../ihyperlink/)
## หมายเหตุ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```




## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IHyperlink](../../ihyperlink/)
* คลาส [String](../../../system/string/)
* คลาส [IHyperlinkManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)