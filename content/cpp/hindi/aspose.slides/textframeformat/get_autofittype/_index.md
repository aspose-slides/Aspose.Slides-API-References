---
title: get_AutofitType()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: टेक्स्ट का ऑटोफिट मोड लौटाता है। पढ़ें TextAutofitType।
type: docs
weight: 222
url: /hi/aspose.slides/textframeformat/get_autofittype/
---
## TextFrameFormat::get_AutofitType() विधि

टेक्स्ट के ऑटोफिट मोड को लौटाता है। पढ़ें [TextAutofitType](../../textautofittype/)।

```cpp
TextAutofitType Aspose::Slides::TextFrameFormat::get_AutofitType() override
```

## टिप्पणियाँ

निम्नलिखित नमूना कोड दिखाता है कि PowerPoint [Presentation](../../presentation/) में आकार को टेक्स्ट के अनुसार फिट करने के लिए कैसे री-साइज़ किया जाए। 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto autoShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 30.0f, 30.0f, 350.0f, 100.0f);
auto portion = System::MakeObject<Portion>(u"lorem ipsum...");
portion->get_PortionFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Black());
portion->get_PortionFormat()->get_FillFormat()->set_FillType(FillType::Solid);
autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Add(portion);
System::SharedPtr<ITextFrameFormat> textFrameFormat = autoShape->get_TextFrame()->get_TextFrameFormat();
textFrameFormat->set_AutofitType(TextAutofitType::Shape);
pres->Save(u"Output-presentation.pptx", SaveFormat::Pptx);
```
निम्नलिखित नमूना कोड दिखाता है कि ओवरफ़्लो पर टेक्स्ट को कैसे सिकुड़ाया जाए। 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto autoShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 30.0f, 30.0f, 350.0f, 100.0f);
auto portion = System::MakeObject<Portion>(u"lorem ipsum...");

portion->get_PortionFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Black());
portion->get_PortionFormat()->get_FillFormat()->set_FillType(FillType::Solid);
autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Add(portion);
System::SharedPtr<ITextFrameFormat> textFrameFormat = autoShape->get_TextFrame()->get_TextFrameFormat();
textFrameFormat->set_AutofitType(TextAutofitType::Normal);
pres->Save(u"Output-presentation.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* एनम [TextAutofitType](../../textautofittype/)
* क्लास [TextFrameFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)