---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides för C++ API-referens
description: Representerar en användares samling av FontFallBack-regler för hantering av typsnittssamlingar för korrekta ersättningar genom fallback-funktionalitet. Läs IFontFallBackRulesCollection.
type: docs
weight: 27
url: /sv/aspose.slides/fontsmanager/get_fontfallbackrulescollection/
---
## FontsManager::get_FontFallBackRulesCollection() metod

Representerar en användares samling av FontFallBack-regler för hantering av typsnittssamlingar för korrekta ersättningar genom fallback-funktionalitet Läs [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> Aspose::Slides::FontsManager::get_FontFallBackRulesCollection() override
```

## Anmärkningar

```cpp
auto pres = MakeObject<Presentation>();
// Hämtning av tom eller förinitierad regelsamling från FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// Lägga till regler i samlingen
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// eller
// Initiering av ny instans av regelsamling
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// Lägga till regler i samlingen
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// och ersättning av befintlig samling med den nya i FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Klass [FontsManager](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)