---
title: idx_get()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Zwraca regułę o podanym indeksie. Tylko do odczytu IFontFallBackRule.
type: docs
weight: 66
url: /pl/aspose.slides/fontfallbackrulescollection/idx_get/
---
## FontFallBackRulesCollection::idx_get(int32_t) metoda


Zwraca regułę o podanym indeksie. Tylko do odczytu [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
System::SharedPtr<IFontFallBackRule> Aspose::Slides::FontFallBackRulesCollection::idx_get(int32_t index) override
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
* Klasa [FontFallBackRulesCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)