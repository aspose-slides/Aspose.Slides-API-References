---
title: GetEffective()
second_title: C++ के लिए Aspose.Slides API रेफ़रेंस
description: विरासत लागू करके प्रभावी टेक्स्ट स्टाइल फ़ॉर्मेटिंग डेटा प्राप्त करता है।
type: docs
weight: 27
url: /hi/aspose.slides/textstyle/geteffective/
---
## TextStyle::GetEffective() विधि


विरासत लागू करके प्रभावी टेक्स्ट शैली स्वरूपण डेटा प्राप्त करता है।

```cpp
System::SharedPtr<ITextStyleEffectiveData> Aspose::Slides::TextStyle::GetEffective() override
```


### रिटर्न वैल्यू

A [ITextStyleEffectiveData](../../itextstyleeffectivedata/).
## टिप्पणी



यह उदाहरण प्रभावी टेक्स्ट शैली गुणों में से कुछ को प्राप्त करने का प्रदर्शन करता है। 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextStyle = shape->get_TextFrame()->get_TextFrameFormat()->get_TextStyle()->GetEffective();

for (int32_t i = 0; i <= 8; i++)
{
    auto effectiveStyleLevel = effectiveTextStyle->GetLevel(i);
    Console::WriteLine(String(u"= Effective paragraph formatting for style level #") + i + u" =");

    Console::WriteLine(String(u"Depth: ") + effectiveStyleLevel->get_Depth());
    Console::WriteLine(String(u"Indent: ") + effectiveStyleLevel->get_Indent());
    Console::WriteLine(String(u"Alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_Alignment()));
    Console::WriteLine(String(u"Font alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_FontAlignment()));
}
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITextStyleEffectiveData](../../itextstyleeffectivedata/)
* Class [TextStyle](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)