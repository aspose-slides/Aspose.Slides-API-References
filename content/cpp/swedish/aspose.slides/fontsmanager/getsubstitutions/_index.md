---
title: GetSubstitutions()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar information om teckensnitt som kommer att ersättas vid presentationens rendering.
type: docs
weight: 66
url: /sv/aspose.slides/fontsmanager/getsubstitutions/
---
## FontsManager::GetSubstitutions() metod


Hämtar information om teckensnitt som kommer att ersättas vid presentationens rendering.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions() override
```


### Returvärde

Samling av alla teckensnittsersättningar [FontSubstitutionInfo](../../fontsubstitutioninfo/).
## Anmärkningar




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```




## FontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) metod


Hämtar information om teckensnitt som kommer att ersättas under rendering av de angivna bildrutorna.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | En array av bildruteindex för vilka fontersättningsinformation ska hämtas, med start från 1. |

### Returvärde

En samling av alla fontersättningar ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) för de angivna bildrutorna.
## Anmärkningar




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Class [FontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)