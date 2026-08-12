---
title: GetEffective()
second_title: Aspose.Slides for C++ एपीआई संदर्भ
description: विरासत लागू करके प्रभावी लाइन फ़ॉर्मेटिंग डेटा प्राप्त करता है।
type: docs
weight: 417
url: /hi/aspose.slides/lineformat/geteffective/
---
## LineFormat::GetEffective() मेथड

विरासत लागू करके प्रभावी लाइन फ़ॉर्मेटिंग डेटा प्राप्त करता है।

```cpp
System::SharedPtr<ILineFormatEffectiveData> Aspose::Slides::LineFormat::GetEffective() override
```

### वापसी मान

A [ILineFormatEffectiveData](../../ilineformateffectivedata/).

## टिप्पणियाँ

यह उदाहरण शेप की प्रभावी लाइन फ़ॉर्मेट गुणों को प्राप्त करने का प्रदर्शन करता है। 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveLineFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_LineFormat()->GetEffective();

Console::WriteLine(String(u"Style: ") + ObjectExt::ToString(effectiveLineFormat->get_Style()));
Console::WriteLine(String(u"Width: ") + effectiveLineFormat->get_Width());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectiveLineFormat->get_FillFormat()->get_FillType()));
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [ILineFormatEffectiveData](../../ilineformateffectivedata/)
* क्लास [LineFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)