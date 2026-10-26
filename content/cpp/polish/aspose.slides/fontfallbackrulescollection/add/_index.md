---
title: Add()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Dodaje określoną regułę FallBack na koniec kolekcji.
type: docs
weight: 40
url: /pl/aspose.slides/fontfallbackrulescollection/add/
---
## FontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) method

Dodaje określoną regułę FallBack na koniec kolekcji.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Określona reguła do dodania |

## Uwagi



```cpp
auto pres = MakeObject<Presentation>();
//Pobieranie pustej lub wstępnie zainicjowanej kolekcji reguł z FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Dodawanie nowej reguły do kolekcji
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IFontFallBackRule](../../ifontfallbackrule/)
* Klasa [FontFallBackRulesCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)