---
title: SetExternalHyperlinkClick()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: क्लिक पर बाहरी हाइपरलिंक सेट करें।
type: docs
weight: 1
url: /hi/aspose.slides/hyperlinkmanager/setexternalhyperlinkclick/
---
## HyperlinkManager::SetExternalHyperlinkClick(System::String) विधि

क्लिक पर बाहरी हाइपरलिंक सेट करें।

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetExternalHyperlinkClick(System::String url) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../../hyperlink/) URL. |

## टिप्पणियाँ

निम्नलिखित नमूना कोड दिखाता है कि कैसे [Hyperlink](../../hyperlink/) के साथ टेक्स्ट बॉक्स जोड़ें। 
```cpp
auto pptxPresentation = System::MakeObject<Presentation>();
// प्रस्तुतिकरण में पहली स्लाइड प्राप्त करता है
auto slide = pptxPresentation->get_Slides()->idx_get(0);

// प्रकार को Rectangle सेट करके एक AutoShape ऑब्जेक्ट जोड़ता है
auto pptxShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 150.0f, 150.0f, 50.0f);
// AutoShape से संबंधित ITextFrame प्रॉपर्टी तक पहुँचता है
pptxShape->AddTextFrame(u"");
auto textFrame = pptxShape->get_TextFrame();
auto portion = textFrame->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);

// फ्रेम में कुछ टेक्स्ट जोड़ता है
portion->set_Text(u"Aspose.Slides");

// भाग के टेक्स्ट के लिए हाइपरलिंक सेट करता है
auto hyperlinkManager = portion->get_PortionFormat()->get_HyperlinkManager();
hyperlinkManager->SetExternalHyperlinkClick(u"http://www.aspose.com");

// PPTX प्रस्तुतिकरण को सहेजता है
pptxPresentation->Save(u"hLinkPPTX_out.pptx", SaveFormat::Pptx);
```

## संदर्भ

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IHyperlink](../../ihyperlink/)
* Class [String](../../../system/string/)
* Class [HyperlinkManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)