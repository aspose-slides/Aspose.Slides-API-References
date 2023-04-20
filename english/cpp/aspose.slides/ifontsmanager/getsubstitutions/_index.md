---
title: GetSubstitutions()
second_title: Aspose.Slides for C++ API Reference
description: Gets the information about fonts that will be replaced on the presentation's rendering.
type: docs
weight: 66
url: /cpp/aspose.slides/ifontsmanager/getsubstitutions/
---
## IFontsManager::GetSubstitutions() method


Gets the information about fonts that will be replaced on the presentation's rendering.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions()=0
```


### Return Value

Collection of all fonts substitution [FontSubstitutionInfo](../../fontsubstitutioninfo/).
## Remarks




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto fontSubstitution : System::IterateOver(pres->get_FontsManager()->GetSubstitutions()))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```




## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)