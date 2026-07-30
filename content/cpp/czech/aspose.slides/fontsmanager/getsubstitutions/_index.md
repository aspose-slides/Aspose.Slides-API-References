---
title: GetSubstitutions()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Získá informace o písmenech, která budou nahrazena při vykreslování prezentace.
type: docs
weight: 66
url: /cs/aspose.slides/fontsmanager/getsubstitutions/
---
## FontsManager::GetSubstitutions() metoda


Získá informace o písmenech, která budou nahrazena při vykreslování prezentace.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions() override
```


### Návratová hodnota

Kolekce všech náhrad písem [FontSubstitutionInfo](../../fontsubstitutioninfo/).
## Poznámky




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```




## FontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) metoda


Získá informace o písmenech, která budou nahrazena při vykreslování určených snímků.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Pole indexů snímků, pro které se mají získat informace o náhradě písem, počínaje 1. |

### Návratová hodnota

Kolekce všech náhrad písem ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) pro určené snímky.
## Poznámky




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Class [FontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)