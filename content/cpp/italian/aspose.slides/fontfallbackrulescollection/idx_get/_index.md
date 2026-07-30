---
title: idx_get()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce la regola all'indice specificato. Solo lettura IFontFallBackRule.
type: docs
weight: 66
url: /it/aspose.slides/fontfallbackrulescollection/idx_get/
---
## FontFallBackRulesCollection::idx_get(int32_t) metodo

Restituisce la regola all'indice specificato. Sola lettura [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
System::SharedPtr<IFontFallBackRule> Aspose::Slides::FontFallBackRulesCollection::idx_get(int32_t index) override
```

## Osservazioni



```cpp
auto pres = MakeObject<Presentation>();
//Ottenimento della collezione di regole vuota o preinizializzata da FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Aggiunta di diverse regole alla collezione
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Recupero dell'oggetto della prima regola nella collezione
auto firstRule = rulesList->idx_get(0);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontFallBackRule](../../ifontfallbackrule/)
* Classe [FontFallBackRulesCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)