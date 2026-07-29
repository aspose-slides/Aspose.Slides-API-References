---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides för C++ API-referens
description: Representerar en användares samling av FontFallBack-regler för hantering av samlingar av teckensnitt för korrekta ersättningar via fallback-funktionalitet Skriv IFontFallBackRulesCollection.
type: docs
weight: 40
url: /sv/aspose.slides/fontsmanager/set_fontfallbackrulescollection/
---
## FontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<Aspose::Slides::IFontFallBackRulesCollection\>) metod


Representerar en användares samling av FontFallBack-regler för hantering av samlingar av teckensnitt för korrekta ersättningar via fallback-funktionalitet Skriv [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
void Aspose::Slides::FontsManager::set_FontFallBackRulesCollection(System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> value) override
```

## Anmärkningar



```cpp
auto pres = MakeObject<Presentation>();
// Hämtar en tom eller förinitialiserad regelkollektion från FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// lägger till regler i samlingen
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// eller
// initiering av ny instans av regelkollektionen
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// lägger till regler i samlingen
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// och ersätter befintlig kollektion med den nya i FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Klass [FontsManager](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)