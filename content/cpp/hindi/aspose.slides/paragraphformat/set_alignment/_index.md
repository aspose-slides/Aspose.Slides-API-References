---
title: set_Alignment()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: पैराग्राफ में बिना विरासत के पाठ संरेखण सेट करता है। TextAlignment लिखें।
type: docs
weight: 14
url: /hi/aspose.slides/paragraphformat/set_alignment/
---
## ParagraphFormat::set_Alignment(TextAlignment) विधि

किसी पैराग्राफ में कोई विरासत नहीं होने पर पाठ संरेखण सेट करता है। लिखें [TextAlignment](../../textalignment/)।

```cpp
void Aspose::Slides::ParagraphFormat::set_Alignment(TextAlignment value) override
```

## टिप्पणियाँ

निम्नलिखित नमूना कोड दर्शाता है कि PowerPoint में टेक्स्ट पैराग्राफ को कैसे संरेखित किया जाए [Presentation](../../presentation/)।
```cpp
auto pres = System::MakeObject<Presentation>(u"ParagraphsAlignment.pptx");

// Accessing first slide
auto slide = pres->get_Slides()->idx_get(0);
// Accessing the first and second placeholder in the slide and typecasting it as AutoShape
System::SharedPtr<ITextFrame> tf1 = (System::ExplicitCast<IAutoShape>(slide->get_Shapes()->idx_get(0)))->get_TextFrame();
System::SharedPtr<ITextFrame> tf2 = (System::ExplicitCast<IAutoShape>(slide->get_Shapes()->idx_get(1)))->get_TextFrame();
// Change the text in both placeholders
tf1->set_Text(u"Center Align by Aspose");
tf2->set_Text(u"Center Align by Aspose");
// Getting the first paragraph of the placeholders
System::SharedPtr<IParagraph> para1 = tf1->get_Paragraphs()->idx_get(0);
System::SharedPtr<IParagraph> para2 = tf2->get_Paragraphs()->idx_get(0);
// Aligning the text paragraph to center
para1->get_ParagraphFormat()->set_Alignment(TextAlignment::Center);
para2->get_ParagraphFormat()->set_Alignment(TextAlignment::Center);
//Writing the presentation as a PPTX file
pres->Save(u"Centeralign_out.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* एन्यूम [TextAlignment](../../textalignment/)
* क्लास [ParagraphFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)