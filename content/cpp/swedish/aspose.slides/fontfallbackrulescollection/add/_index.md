---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägg till en specificerad FallBack-regel i slutet av samlingen.
type: docs
weight: 40
url: /sv/aspose.slides/fontfallbackrulescollection/add/
---
## FontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) metod

Lägg till en specificerad FallBack-regel i slutet av samlingen.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule) override
```

### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Specificerad regel för att lägga till |
## Anmärkningar

```cpp
auto pres = MakeObject<Presentation>();
//Hämtar en tom eller förinitialiserad regelssamling från FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Lägger till en ny regel i samlingen
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IFontFallBackRule](../../ifontfallbackrule/)
* Klass [FontFallBackRulesCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)