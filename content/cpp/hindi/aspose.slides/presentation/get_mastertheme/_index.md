---
title: get_MasterTheme()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: "मास्टर थीम लौटाता है। केवल पढ़ने के लिए Theme::IMasterTheme."
type: docs
weight: 404
url: /hi/aspose.slides/presentation/get_mastertheme/
---
## Presentation::get_MasterTheme() method

मास्टर थीम लौटाता है। केवल पढ़ने के लिये [Theme::IMasterTheme](../../../aspose.slides.theme/imastertheme/).

```cpp
System::SharedPtr<Theme::IMasterTheme> Aspose::Slides::Presentation::get_MasterTheme() override
```

## टिप्पणियाँ

निम्नलिखित उदाहरण दर्शाते हैं कि PowerPoint के तत्वों के भागों को बदलकर थीम प्रभाव को कैसे बदलें [Presentation](../)। 
```cpp
// एक प्रस्तुति फ़ाइल का प्रतिनिधित्व करने वाला प्रस्तुति ऑब्जेक्ट बनाएं
auto pres = System::MakeObject<Presentation>(u"Subtle_Moderate_Intense.pptx");
auto masterTheme = pres->get_MasterTheme();
auto formatScheme = masterTheme->get_FormatScheme();

formatScheme->get_LineStyles()->idx_get(0)->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
formatScheme->get_FillStyles()->idx_get(2)->set_FillType(FillType::Solid);
formatScheme->get_FillStyles()->idx_get(2)->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
formatScheme->get_EffectStyles()->idx_get(2)->get_EffectFormat()->get_OuterShadowEffect()->set_Distance(10.0f);
pres->Save(u"Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMasterTheme](../../../aspose.slides.theme/imastertheme/)
* क्लास [Presentation](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)