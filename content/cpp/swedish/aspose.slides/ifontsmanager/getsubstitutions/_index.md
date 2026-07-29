---
title: GetSubstitutions()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar informationen om teckensnitt som kommer att ersättas vid presentationens rendering.
type: docs
weight: 66
url: /sv/aspose.slides/ifontsmanager/getsubstitutions/
---
## IFontsManager::GetSubstitutions() metod


Hämtar informationen om teckensnitt som kommer att ersättas vid presentationens rendering.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions()=0
```


### Returvärde

Samling av alla teckensnittssubstitutioner [FontSubstitutionInfo](../../fontsubstitutioninfo/).
## Anmärkningar




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```




## IFontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) metod


Hämtar informationen om teckensnitt som kommer att ersättas under rendering av de specificerade bilderna.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides)=0
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | En array av bildindex för vilka teckensnittssubstitutionsinformation ska hämtas, med början från 1. |

### Returvärde

En samling av alla teckensnittssubstitutioner ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) för de specificerade bilderna.
## Anmärkningar




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klass [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Klass [IFontsManager](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)