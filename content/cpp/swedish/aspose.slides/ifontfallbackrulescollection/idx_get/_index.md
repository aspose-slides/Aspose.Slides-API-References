---
title: idx_get()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar regeln på det angivna indexet. Skrivskyddad IFontFallBackRule.
type: docs
weight: 1
url: /sv/aspose.slides/ifontfallbackrulescollection/idx_get/
---
## IFontFallBackRulesCollection::idx_get(int32_t) metod


Hämtar regeln på det angivna indexet. Skrivskyddad [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
virtual System::SharedPtr<IFontFallBackRule> Aspose::Slides::IFontFallBackRulesCollection::idx_get(int32_t index)=0
```

## Anmärkningar



```cpp
auto pres = MakeObject<Presentation>();
//Hämtar en tom eller förinitierad samling av regler från FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Lägger till flera regler i samlingen
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Hämtar objektet för den första regeln i samlingen
auto firstRule = rulesList->idx_get(0);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IFontFallBackRule](../../ifontfallbackrule/)
* Klass [IFontFallBackRulesCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)