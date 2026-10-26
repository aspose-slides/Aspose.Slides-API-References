---
title: get_WrapText()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: True यदि पाठ TextFrame की सीमाओं पर लपेटा गया हो। पढ़ें NullableBool.
type: docs
weight: 118
url: /hi/aspose.slides/textframeformat/get_wraptext/
---
## TextFrameFormat::get_WrapText() विधि

**True** यदि पाठ [TextFrame](../../textframe/) की सीमाओं पर लपेटा गया है। पढ़ें [NullableBool](../../nullablebool/).

```cpp
NullableBool Aspose::Slides::TextFrameFormat::get_WrapText() override
```

## टिप्पणियाँ

नीचे दिया गया नमूना कोड दिखाता है कि [Presentation](../../presentation/) में पाठ को कैसे लपेटा जाए। 
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

* एन्यूम [NullableBool](../../nullablebool/)
* क्लास [TextFrameFormat](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)