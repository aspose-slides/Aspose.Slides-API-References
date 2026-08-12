---
title: set_WrapText()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: True यदि पाठ TextFrame की मार्जिन पर रैप किया गया हो। NullableBool लिखें।
type: docs
weight: 131
url: /hi/aspose.slides/textframeformat/set_wraptext/
---
## TextFrameFormat::set_WrapText(NullableBool) विधि


**True** यदि पाठ [TextFrame](../../textframe/) की मार्जिन पर रैप किया जाता है। [NullableBool](../../nullablebool/) लिखें।

```cpp
void Aspose::Slides::TextFrameFormat::set_WrapText(NullableBool value) override
```

## टिप्पणियाँ


नीचे दिया गया नमूना कोड दिखाता है कि [Presentation](../../presentation/) में पाठ को कैसे रैप किया जाए। 
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

## संबंधित देखें

* Enum [NullableBool](../../nullablebool/)
* क्लास [TextFrameFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)