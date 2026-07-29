---
title: idx_get()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar regeln på det angivna indexet. Skrivskyddad IFontFallBackRule.
type: docs
weight: 66
url: /sv/aspose.slides/fontfallbackrulescollection/idx_get/
---
## FontFallBackRulesCollection::idx_get(int32_t) metod


Hämtar regeln på det angivna indexet. Skrivskyddad [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
System::SharedPtr<IFontFallBackRule> Aspose::Slides::FontFallBackRulesCollection::idx_get(int32_t index) override
```

## Anmärkningar



```cpp
auto pres = MakeObject<Presentation>();
//Hämtar tom eller förinitialiserad regelkollektion från FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Lägger till flera regler i kollektionen
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Hämtar objektet för den första regeln i kollektionen
auto firstRule = rulesList->idx_get(0);
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IFontFallBackRule](../../ifontfallbackrule/)
* Klass [FontFallBackRulesCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)