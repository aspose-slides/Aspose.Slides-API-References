---
title: GetEffective()
second_title: Aspose.Slides for C++ API Reference
description: Gets effective theme data with the inheritance applied.
type: docs
weight: 53
url: /aspose.slides.theme/theme/geteffective/
---
## Theme::GetEffective() method


Gets effective theme data with the inheritance applied.

```cpp
System::SharedPtr<IThemeEffectiveData> Aspose::Slides::Theme::Theme::GetEffective() override
```


### Return Value

A [IThemeEffectiveData](../../ithemeeffectivedata/).
## Remarks



This example demonstrates getting effective theme properties. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveTheme = pres->get_Slides()->idx_get(0)->get_ThemeManager()->get_OverrideTheme()->GetEffective();

Console::WriteLine(String(u"Font scheme name: ") + effectiveTheme->get_FontScheme()->get_Name());
Console::WriteLine(String(u"Major latin font: ") + effectiveTheme->get_FontScheme()->get_Major()->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Minor latin font: ") + effectiveTheme->get_FontScheme()->get_Minor()->get_LatinFont()->get_FontName());
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IThemeEffectiveData](../../ithemeeffectivedata/)
* Class [Theme](../)
* Namespace [Aspose::Slides::Theme](../../)
* Library [Aspose.Slides](../../../)