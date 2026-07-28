---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides for C++ Referencja API
description: Reprezentuje kolekcję reguł FontFallBack użytkownika do zarządzania kolekcjami czcionek w celu prawidłowych zamian przy użyciu funkcji fallback. Przeczytaj IFontFallBackRulesCollection.
type: docs
weight: 27
url: /pl/aspose.slides/fontsmanager/get_fontfallbackrulescollection/
---
## FontsManager::get_FontFallBackRulesCollection() metoda

Reprezentuje kolekcję reguł FontFallBack użytkownika do zarządzania kolekcjami czcionek w celu prawidłowej zamiany przy użyciu funkcji fallback. Przeczytaj [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> Aspose::Slides::FontsManager::get_FontFallBackRulesCollection() override
```

## Uwagi

```cpp
auto pres = MakeObject<Presentation>();
// Pobieranie pustej lub wstępnie zainicjalizowanej kolekcji reguł z FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// dodawanie reguł do kolekcji
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// lub
// inicjalizacja nowej instancji kolekcji reguł
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// dodawanie reguł do kolekcji
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// oraz zamiana istniejącej kolekcji na nową w FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Klasa [FontsManager](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)