---
title: GetEffective()
second_title: Aspose.Slides for C++ API संदर्भ
description: विरासत लागू होते हुए प्रभावी टेक्स्ट फ़्रेम फ़ॉर्मेटिंग डेटा प्राप्त करता है।
type: docs
weight: 391
url: /hi/aspose.slides/textframeformat/geteffective/
---
## TextFrameFormat::GetEffective() विधि

विरासत लागू होने पर प्रभावी टेक्स्ट फ़्रेम फ़ॉर्मेटिंग डेटा प्राप्त करता है।

```cpp
System::SharedPtr<ITextFrameFormatEffectiveData> Aspose::Slides::TextFrameFormat::GetEffective() override
```

### रिटर्न वैल्यू

एक [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/).
## टिप्पणियाँ

यह उदाहरण प्रभावी टेक्स्ट फ़्रेम फ़ॉर्मेटिंग गुणों में से कुछ प्राप्त करने को दर्शाता है। 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextFrameFormat = shape->get_TextFrame()->get_TextFrameFormat()->GetEffective();

Console::WriteLine(String(u"Anchoring type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_AnchoringType()));
Console::WriteLine(String(u"Autofit type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_AutofitType()));
Console::WriteLine(String(u"Text vertical type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_TextVerticalType()));
Console::WriteLine(u"Margins");
Console::WriteLine(String(u"   Left: ") + effectiveTextFrameFormat->get_MarginLeft());
Console::WriteLine(String(u"   Top: ") + effectiveTextFrameFormat->get_MarginTop());
Console::WriteLine(String(u"   Right: ") + effectiveTextFrameFormat->get_MarginRight());
Console::WriteLine(String(u"   Bottom: ") + effectiveTextFrameFormat->get_MarginBottom());
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/)
* क्लास [TextFrameFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)