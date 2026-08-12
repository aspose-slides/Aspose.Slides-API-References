---
title: GetEffective()
second_title: Aspose.Slides for C++ API संदर्भ
description: विरासत लागू होने के साथ प्रभावी थीम डेटा प्राप्त करता है।
type: docs
weight: 53
url: /hi/aspose.slides.theme/theme/geteffective/
---
## Theme::GetEffective() मेथड


विरासत लागू होने के साथ प्रभावी थीम डेटा प्राप्त करता है।

```cpp
System::SharedPtr<IThemeEffectiveData> Aspose::Slides::Theme::Theme::GetEffective() override
```


### रिटर्न मान

एक [IThemeEffectiveData](../../ithemeeffectivedata/).
## टिप्पणियाँ



यह उदाहरण प्रभावी थीम प्रॉपर्टीज़ को प्राप्त करना प्रदर्शित करता है। 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveTheme = pres->get_Slides()->idx_get(0)->get_ThemeManager()->get_OverrideTheme()->GetEffective();

Console::WriteLine(String(u"Font scheme name: ") + effectiveTheme->get_FontScheme()->get_Name());
Console::WriteLine(String(u"Major latin font: ") + effectiveTheme->get_FontScheme()->get_Major()->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Minor latin font: ") + effectiveTheme->get_FontScheme()->get_Minor()->get_LatinFont()->get_FontName());
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IThemeEffectiveData](../../ithemeeffectivedata/)
* क्लास [Theme](../)
* नेमस्पेस [Aspose::Slides::Theme](../../)
* Library [Aspose.Slides](../../../)