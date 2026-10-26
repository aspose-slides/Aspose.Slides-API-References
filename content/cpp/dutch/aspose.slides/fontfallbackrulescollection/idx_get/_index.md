---
title: idx_get()
second_title: Aspose.Slides voor C++ API Referentie
description: Haalt de regel op de opgegeven index op. Alleen-lezen IFontFallBackRule.
type: docs
weight: 66
url: /nl/aspose.slides/fontfallbackrulescollection/idx_get/
---
## FontFallBackRulesCollection::idx_get(int32_t) methode

Haalt de regel op de opgegeven index. Alleen-lezen [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
System::SharedPtr<IFontFallBackRule> Aspose::Slides::FontFallBackRulesCollection::idx_get(int32_t index) override
```

## Opmerkingen

```cpp
auto pres = MakeObject<Presentation>();
//Ophalen van een lege of vooraf geïnitialiseerde regelsverzameling van FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Toevoegen van verschillende regels aan de collectie
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Ophalen van het object van de eerste regel in de collectie
auto firstRule = rulesList->idx_get(0);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IFontFallBackRule](../../ifontfallbackrule/)
* Klasse [FontFallBackRulesCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)