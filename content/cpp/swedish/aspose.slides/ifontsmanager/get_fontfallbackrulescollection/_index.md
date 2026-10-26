---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides för C++ API-referens
description: Representerar en användares samling av FontFallBack-regler för hantering av teckensnittssamlingar för korrekta ersättningar via fallback-funktionalitet Läs IFontFallBackRulesCollection.
type: docs
weight: 27
url: /sv/aspose.slides/ifontsmanager/get_fontfallbackrulescollection/
---
## IFontsManager::get_FontFallBackRulesCollection() metod

Representerar en användares samling av FontFallBack-regler för hantering av teckensnittssamlingar för korrekta ersättningar via fallback-funktionalitet Läs [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual System::SharedPtr<IFontFallBackRulesCollection> Aspose::Slides::IFontsManager::get_FontFallBackRulesCollection()=0
```

## Anmärkningar

```cpp
auto pres = MakeObject<Presentation>();
// Hämtar en tom eller förinitierad regelssamling från FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// Lägger till regler i samlingen
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// eller
// Initiering av en ny instans av regelssamling
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// Lägger till regler i samlingen
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// och ersätter den befintliga samlingen med den nya i FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Klass [IFontsManager](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)