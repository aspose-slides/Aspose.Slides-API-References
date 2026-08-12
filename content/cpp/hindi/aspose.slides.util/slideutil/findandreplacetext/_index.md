---
title: FindAndReplaceText()
second_title: Aspose.Slides C++ के लिए API रेफ़रेंस
description: दिए गए स्वरूप के साथ प्रस्तुत  ि में पाठ को खोजता और प्रतिस्थापित करता है
type: docs
weight: 40
url: /hi/aspose.slides.util/slideutil/findandreplacetext/
---
## SlideUtil::FindAndReplaceText(System::SharedPtr\<IPresentation\>, bool, System::String, System::String, System::SharedPtr\<PortionFormat\>) मेथड


प्रस्तुति में दिए गए प्रारूप के साथ पाठ को खोजता और प्रतिस्थापित करता है

```cpp
static void Aspose::Slides::Util::SlideUtil::FindAndReplaceText(System::SharedPtr<IPresentation> presentation, bool withMasters, System::String find, System::String replace, System::SharedPtr<PortionFormat> format=nullptr)
```


### आर्ग्यूमेंट्स

| पैरामी터 | प्रकार | विवरण |
| --- | --- | --- |
| presentation | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | स्कैन की गई प्रस्तुति। |
| withMasters | **bool** | निर्धारित करता है कि मुख्य स्लाइड स्कैन की जाएँ या नहीं। |
| find | [System::String](../../../system/string/) | खोजने के लिए स्ट्रिंग मान। |
| replace | [System::String](../../../system/string/) | प्रतिस्थापित करने के लिए स्ट्रिंग मान। |
| format | [System::SharedPtr](../../../system/sharedptr/)\<[PortionFormat](../../../aspose.slides/portionformat/)\> | टेक्स्ट भाग को प्रतिस्थापित करने का प्रारूप। यदि null हो तो पाए गए स्ट्रिंग के पहले अक्षर का प्रारूप उपयोग किया जाएगा |
## टिप्पणी




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto format = System::MakeObject<PortionFormat>();
format->set_FontHeight(24.0f);
format->set_FontItalic(NullableBool::True);
auto fillFormat = format->get_FillFormat();
fillFormat->set_FillType(FillType::Solid);
fillFormat->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());

SlideUtil::FindAndReplaceText(pres, true, u"[this block] ", u"my text ", format);
pres->Save(u"replaced", SaveFormat::Pptx);
```




## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IPresentation](../../../aspose.slides/ipresentation/)
* क्लास [String](../../../system/string/)
* क्लास [PortionFormat](../../../aspose.slides/portionformat/)
* क्लास [SlideUtil](../)
* नेमस्पेस [Aspose::Slides::Util](../../)
* लाइब्रेरी [Aspose.Slides](../../../)