---
title: GetSubstitutions()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de informatie op over lettertypen die tijdens het renderen van de presentatie worden vervangen.
type: docs
weight: 66
url: /nl/aspose.slides/fontsmanager/getsubstitutions/
---
## FontsManager::GetSubstitutions() methode

Haalt de informatie op over lettertypen die tijdens het renderen van de presentatie worden vervangen.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions() override
```

### Retourwaarde

Collectie van alle fontersubstituties [FontSubstitutionInfo](../../fontsubstitutioninfo/).

## Opmerkingen

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## FontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) methode

Haalt de informatie op over lettertypen die tijdens het renderen van de opgegeven dia’s worden vervangen.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Een array van dia-indexen waarvoor de fontersubstitutie-informatie moet worden opgehaald, beginnend bij 1. |

### Retourwaarde

Een collectie van alle fontersubstituties ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) voor de opgegeven dia’s.

## Opmerkingen

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klasse [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Klasse [FontsManager](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)