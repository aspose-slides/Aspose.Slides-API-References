---
title: GetEffective()
second_title: Aspose.Slides for C++ API संदर्भ
description: विरासत लागू करके प्रभावी पैराग्राफ फ़ॉर्मेटिंग डेटा प्राप्त करता है।
type: docs
weight: 365
url: /hi/aspose.slides/paragraphformat/geteffective/
---
## ParagraphFormat::GetEffective() method


विरासत लागू करके प्रभावी पैराग्राफ फ़ॉर्मेटिंग डेटा प्राप्त करता है।

```cpp
System::SharedPtr<IParagraphFormatEffectiveData> Aspose::Slides::ParagraphFormat::GetEffective() override
```


### रिटर्न वैल्यू

एक [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)।
## टिप्पणियाँ



यह उदाहरण कुछ प्रभावी पैराग्राफ फ़ॉर्मेट गुण प्राप्त करने को दर्शाता है। 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveParagraphFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->GetEffective();

Console::WriteLine(String(u"Text alignment: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Alignment()));
Console::WriteLine(String(u"Indent: ") + effectiveParagraphFormat->get_Indent());
Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Bullet()->get_Type()));
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)
* क्लास [ParagraphFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)