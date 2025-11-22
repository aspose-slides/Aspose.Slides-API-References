---
title: GetSubstitutions()
second_title: Aspose.Slides for C++ API Reference
description: Gets the information about fonts that will be replaced on the presentation's rendering.
type: docs
weight: 66
url: /aspose.slides/ifontsmanager/getsubstitutions/
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

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```




## IFontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) method


Gets the information about fonts that will be replaced during rendering of the specified slides.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | An array of slide indexes for which to retrieve font substitution information, starting from 1. |

### Return Value

A collection of all font substitutions ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) for the specified slides.
## Remarks




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)