---
title: Remove()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort den första förekomsten av en specifik FallBack-regel från samlingen.
type: docs
weight: 53
url: /sv/aspose.slides/fontfallbackrulescollection/remove/
---
## FontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) metod


Tar bort den första förekomsten av en specifik FallBack-regel från samlingen.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Regelen som ska tas bort från samlingen. |
## Anmärkningar



```cpp
auto pres = MakeObject<Presentation>();
//Hämtar en tom eller förinitierad regellsamling från FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Lägger till flera regler i samlingen
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Hämtar objektet för den första regeln i samlingen
auto firstRule = rulesList->idx_get(0);
//Tar bort
rulesList->Remove(firstRule);
```


## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IFontFallBackRule](../../ifontfallbackrule/)
* Klass [FontFallBackRulesCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)