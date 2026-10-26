---
title: get_WrapText()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: True ถ้าข้อความถูกห่อรอบที่ขอบของ TextFrame. อ่าน NullableBool.
type: docs
weight: 118
url: /th/aspose.slides/textframeformat/get_wraptext/
---
## TextFrameFormat::get_WrapText() เมธอด

**True** ถ้าข้อความถูกห่อรอบที่ขอบของ [TextFrame](../../textframe/). อ่าน [NullableBool](../../nullablebool/).

```cpp
NullableBool Aspose::Slides::TextFrameFormat::get_WrapText() override
```

## หมายเหตุ

โค้ดตัวอย่างต่อไปนี้แสดงวิธีการห่อข้อความใน [Presentation](../../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto autoShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 30.0f, 30.0f, 350.0f, 100.0f);
auto portion = System::MakeObject<Portion>(u"lorem ipsum...");
portion->get_PortionFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Black());
portion->get_PortionFormat()->get_FillFormat()->set_FillType(FillType::Solid);
autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Add(portion);
auto textFrameFormat = autoShape->get_TextFrame()->get_TextFrameFormat();
textFrameFormat->set_WrapText(NullableBool::True);
pres->Save(u"Output-presentation.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Enum [NullableBool](../../nullablebool/)
* คลาส [TextFrameFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)