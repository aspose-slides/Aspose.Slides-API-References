---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides dla API C++
description: Reprezentuje kolekcję reguł FontFallBack użytkownika służącą do zarządzania kolekcjami czcionek w celu prawidłowych podstawień przy użyciu funkcji awaryjnej Przeczytaj IFontFallBackRulesCollection.
type: docs
weight: 27
url: /pl/aspose.slides/ifontsmanager/get_fontfallbackrulescollection/
---
## IFontsManager::get_FontFallBackRulesCollection() metoda


Reprezentuje kolekcję reguł FontFallBack użytkownika służącą do zarządzania kolekcjami czcionek w celu prawidłowych podstawień przy użyciu funkcji awaryjnej Przeczytaj [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual System::SharedPtr<IFontFallBackRulesCollection> Aspose::Slides::IFontsManager::get_FontFallBackRulesCollection()=0
```

## Uwagi



```cpp
auto pres = MakeObject<Presentation>();
// Pobieranie pustej lub wstępnie zainicjowanej kolekcji reguł z FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// dodawanie reguł do kolekcji
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// lub
// inicjalizacja nowej instancji kolekcji reguł
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// dodawanie reguł do kolekcji
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// oraz zastąpienie istniejącej kolekcji nową w FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Klasa [IFontsManager](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)