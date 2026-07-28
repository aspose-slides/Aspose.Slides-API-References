---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides dla C++ API Reference
description: Reprezentuje kolekcję reguł FontFallBack użytkownika służącą do zarządzania zestawami czcionek w celu prawidłowych zamian przy użyciu funkcji fallback. Zapisz IFontFallBackRulesCollection.
type: docs
weight: 40
url: /pl/aspose.slides/fontsmanager/set_fontfallbackrulescollection/
---
## FontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<Aspose::Slides::IFontFallBackRulesCollection\>) metoda


Reprezentuje kolekcję reguł FontFallBack użytkownika służącą do zarządzania zestawami czcionek w celu właściwych zamian przy użyciu funkcji fallback. Zapisz [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
void Aspose::Slides::FontsManager::set_FontFallBackRulesCollection(System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> value) override
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
* Klasa [FontsManager](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)