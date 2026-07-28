---
title: idx_get()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Pobiera regułę pod określonym indeksem. Tylko do odczytu IFontFallBackRule.
type: docs
weight: 1
url: /pl/aspose.slides/ifontfallbackrulescollection/idx_get/
---
## IFontFallBackRulesCollection::idx_get(int32_t) metoda


Pobiera regułę pod określonym indeksem. Tylko do odczytu [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
virtual System::SharedPtr<IFontFallBackRule> Aspose::Slides::IFontFallBackRulesCollection::idx_get(int32_t index)=0
```

## Uwagi



```cpp
auto pres = MakeObject<Presentation>();
//Pobieranie pustej lub wstępnie zainicjowanej kolekcji reguł z FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Dodawanie kilku reguł do kolekcji
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Pobieranie obiektu pierwszej reguły w kolekcji
auto firstRule = rulesList->idx_get(0);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IFontFallBackRule](../../ifontfallbackrule/)
* Klasa [IFontFallBackRulesCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)