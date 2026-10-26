---
title: idx_get()
second_title: Aspose.Slides pro C++ API Reference
description: Získá pravidlo na zadaném indexu. Pouze ke čtení IFontFallBackRule.
type: docs
weight: 66
url: /cs/aspose.slides/fontfallbackrulescollection/idx_get/
---
## FontFallBackRulesCollection::idx_get(int32_t) metoda


Získá pravidlo na zadaném indexu. Pouze ke čtení [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
System::SharedPtr<IFontFallBackRule> Aspose::Slides::FontFallBackRulesCollection::idx_get(int32_t index) override
```

## Poznámky



```cpp
auto pres = MakeObject<Presentation>();
//Získání prázdné nebo předinicializované kolekce pravidel z FontsManageru
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Přidání několika pravidel do kolekce
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Získání objektu prvního pravidla v kolekci
auto firstRule = rulesList->idx_get(0);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IFontFallBackRule](../../ifontfallbackrule/)
* Třída [FontFallBackRulesCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)