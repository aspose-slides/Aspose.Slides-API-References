---
title: GetSubstitutions()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de informatie op over lettertypen die tijdens het renderen van de presentatie worden vervangen.
type: docs
weight: 66
url: /nl/aspose.slides/ifontsmanager/getsubstitutions/
---
## IFontsManager::GetSubstitutions() methode

Haalt de informatie op over lettertypen die tijdens het renderen van de presentatie worden vervangen.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions()=0
```

### Retourwaarde

Collectie van alle lettertypevervangingen [FontSubstitutionInfo](../../fontsubstitutioninfo/).

## Opmerkingen

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## IFontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) methode

Haalt de informatie op over lettertypen die tijdens het renderen van de opgegeven dia's worden vervangen.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Een array van dia-indexen waarvoor lettertypevervangingsinformatie moet worden opgehaald, beginnend bij 1. |

### Retourwaarde

Een collectie van alle lettertypevervangingen ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) voor de opgegeven dia's.

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
* Klasse [IFontsManager](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)