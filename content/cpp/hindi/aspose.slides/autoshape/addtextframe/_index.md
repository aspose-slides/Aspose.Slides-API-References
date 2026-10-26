---
title: AddTextFrame()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक आकार में नया TextFrame जोड़ता है। यदि आकार में पहले से TextFrame है तो केवल उसके पाठ को बदलता है।
type: docs
weight: 66
url: /hi/aspose.slides/autoshape/addtextframe/
---
## AutoShape::AddTextFrame(System::String) विधि

एक नया [TextFrame](../../textframe/) एक आकार में जोड़ता है। यदि आकार में पहले से [TextFrame](../../textframe/) है तो केवल उसके पाठ को बदलता है।

```cpp
System::SharedPtr<ITextFrame> Aspose::Slides::AutoShape::AddTextFrame(System::String text) override
```

### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | एक नए [TextFrame](../../textframe/) के लिए डिफ़ॉल्ट पाठ। |
## टिप्पणी

निम्नलिखित नमूना कोड दर्शाता है कि PowerPoint [Presentation](../../presentation/) में वॉटरमार्क पाठ कैसे जोड़ें। 
```cpp
auto presentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 150.0f, 50.0f);
System::SharedPtr<ITextFrame> watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
```
निम्न उदाहरण दिखाता है कि [Slide](../../slide/) पर टेक्स्ट बॉक्स कैसे बनाएं। 
```cpp
// Presentation को instantiate करता है
auto pres = System::MakeObject<Presentation>();

// प्रस्तुति में पहली स्लाइड प्राप्त करता है
auto slide = pres->get_Slides()->idx_get(0);
// Rectangle प्रकार के साथ AutoShape जोड़ता है
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
// Rectangle में TextFrame जोड़ता है
shape->AddTextFrame(u" ");
// टेक्स्ट फ्रेम तक पहुंचता है
auto txtFrame = shape->get_TextFrame();
// टेक्स्ट फ्रेम के लिए Paragraph ऑब्जेक्ट बनाता है
auto para = txtFrame->get_Paragraphs()->idx_get(0);
// पैराग्राफ के लिए Portion ऑब्जेक्ट बनाता है
auto portion = para->get_Portions()->idx_get(0);
// टेक्स्ट सेट करता है
portion->set_Text(u"Aspose TextBox");
// प्रस्तुति को डिस्क पर सहेजता है
pres->Save(u"TextBox_out.pptx", SaveFormat::Pptx);
```
निम्न उदाहरण दिखाता है कि टेक्स्ट बॉक्स में कॉलम कैसे जोड़ें। 
```cpp
auto presentation = System::MakeObject<Presentation>();

// प्रस्तुति में पहली स्लाइड प्राप्त करता है
auto slide = presentation->get_Slides()->idx_get(0);
// प्रकार को Rectangle सेट करके AutoShape जोड़ता है
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 300.0f, 300.0f);
// Rectangle में TextFrame जोड़ता है
shape->AddTextFrame(System::String(u"All these columns are limited to be within a single text container -- ") +
                    u"you can add or delete text and the new or remaining text automatically adjusts " +
                    u"itself to flow within the container. You cannot have text flow from one container " +
                    u"to other though -- we told you PowerPoint's column options for text are limited!");
// TextFrame का टेक्स्ट फॉर्मेट प्राप्त करता है
auto format = shape->get_TextFrame()->get_TextFrameFormat();
// TextFrame में कॉलमों की संख्या निर्दिष्ट करता है
format->set_ColumnCount(3);
// कॉलमों के बीच स्पेसिंग निर्दिष्ट करता है
format->set_ColumnSpacing(10);
// प्रस्तुति को सहेजता है
presentation->Save(u"ColumnCount.pptx", SaveFormat::Pptx);
```

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [ITextFrame](../../itextframe/)
* क्लास [String](../../../system/string/)
* क्लास [AutoShape](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)