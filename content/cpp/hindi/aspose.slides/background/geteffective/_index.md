---
title: GetEffective()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: इनहेरिटेंस लागू होने पर प्रभावी बैकग्राउंड डेटा प्राप्त करता है।
type: docs
weight: 118
url: /hi/aspose.slides/background/geteffective/
---
## Background::GetEffective() मेथड

इनहेरिटेंस लागू होने पर प्रभावी बैकग्राउंड डेटा प्राप्त करता है।

```cpp
System::SharedPtr<IBackgroundEffectiveData> Aspose::Slides::Background::GetEffective() override
```

### रिटर्न वैल्यू

एक [IBackgroundEffectiveData](../../ibackgroundeffectivedata/).

## टिप्पणी



यह उदाहरण प्रभावी बैकग्राउंड गुण प्राप्त करने को दर्शाता है। 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveBackground = pres->get_Slides()->idx_get(0)->get_Background()->GetEffective();
Console::WriteLine(String(u"Background fill type: ") + ObjectExt::ToString(effectiveBackground->get_FillFormat()->get_FillType()));
Console::WriteLine(String(u"Any effects applied: ") + !effectiveBackground->get_EffectFormat()->get_IsNoEffects());
```

## संबंधित देखें

* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IBackgroundEffectiveData](../../ibackgroundeffectivedata/)
* क्लास [Background](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)