---
title: idx_get()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Získá pravidlo na zadaném indexu. Pouze pro čtení IFontFallBackRule.
type: docs
weight: 1
url: /cs/aspose.slides/ifontfallbackrulescollection/idx_get/
---
## IFontFallBackRulesCollection::idx_get(int32_t) metoda


Získá pravidlo na zadaném indexu. Pouze pro čtení [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
virtual System::SharedPtr<IFontFallBackRule> Aspose::Slides::IFontFallBackRulesCollection::idx_get(int32_t index)=0
```

## Poznámky



```cpp
auto pres = MakeObject<Presentation>();
//Získání prázdné nebo předinicializované kolekce pravidel z FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Přidání několika pravidel do kolekce
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Získání objektu prvního pravidla v kolekci
auto firstRule = rulesList->idx_get(0);
```

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IFontFallBackRule](../../ifontfallbackrule/)
* Třída [IFontFallBackRulesCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)