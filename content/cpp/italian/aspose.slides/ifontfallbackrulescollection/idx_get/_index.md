---
title: idx_get()
second_title: Riferimento API Aspose.Slides per C++
description: Ottiene la regola all'indice specificato. Di sola lettura IFontFallBackRule.
type: docs
weight: 1
url: /it/aspose.slides/ifontfallbackrulescollection/idx_get/
---
## IFontFallBackRulesCollection::idx_get(int32_t) metodo


Ottiene la regola all'indice specificato. Di sola lettura [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
virtual System::SharedPtr<IFontFallBackRule> Aspose::Slides::IFontFallBackRulesCollection::idx_get(int32_t index)=0
```

## Osservazioni



```cpp
auto pres = MakeObject<Presentation>();
//Recupero della collezione di regole vuota o preinizializzata da FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Aggiunta di diverse regole alla collezione
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Recupero dell'oggetto della prima regola nella collezione
auto firstRule = rulesList->idx_get(0);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontFallBackRule](../../ifontfallbackrule/)
* Class [IFontFallBackRulesCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)