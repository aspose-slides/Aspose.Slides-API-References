---
title: idx_get()
second_title: Aspose.Slides voor C++ API Referentie
description: Haalt de regel op op de opgegeven index. Alleen-lezen IFontFallBackRule.
type: docs
weight: 1
url: /nl/aspose.slides/ifontfallbackrulescollection/idx_get/
---
## IFontFallBackRulesCollection::idx_get(int32_t) methode

Haalt de regel op op de opgegeven index. Alleen-lezen [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
virtual System::SharedPtr<IFontFallBackRule> Aspose::Slides::IFontFallBackRulesCollection::idx_get(int32_t index)=0
```

## Opmerkingen

```cpp
auto pres = MakeObject<Presentation>();
//Lege of vooraf geïnitialiseerde regelscollectie ophalen van FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Meerdere regels toevoegen aan de collectie
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Object van de eerste regel in de collectie ophalen
auto firstRule = rulesList->idx_get(0);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IFontFallBackRule](../../ifontfallbackrule/)
* Klasse [IFontFallBackRulesCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)