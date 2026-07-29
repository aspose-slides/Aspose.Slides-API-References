---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides för C++ API-referens
description: Representerar en användares samling av FontFallBack-regler för hantering av samlingar av teckensnitt för korrekta ersättningar via fallback-funktionalitet Skriv IFontFallBackRulesCollection.
type: docs
weight: 40
url: /sv/aspose.slides/ifontsmanager/set_fontfallbackrulescollection/
---
## IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<IFontFallBackRulesCollection\>) metod


Representerar en användares samling av FontFallBack-regler för hantering av samlingar av teckensnitt för korrekta ersättningar genom fallback-funktionalitet Skriv [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual void Aspose::Slides::IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr<IFontFallBackRulesCollection> value)=0
```

## Anmärkningar



```cpp
auto pres = MakeObject<Presentation>();
// Hämtar en tom eller förinitierad regeluppsättning från FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// lägger till regler i samlingen
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// eller
// initialisering av en ny instans av regeluppsättningen
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// lägger till regler i samlingen
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// och ersätter befintlig samling med den nya i FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)