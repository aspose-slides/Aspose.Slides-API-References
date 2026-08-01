---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides voor C++ API-referentie
description: Vertegenwoordigt een collectie van FontFallBack-regels van een gebruiker voor het beheren van collecties van lettertypen voor correcte vervangingen door fallback-functionaliteit. Lees IFontFallBackRulesCollection.
type: docs
weight: 27
url: /nl/aspose.slides/fontsmanager/get_fontfallbackrulescollection/
---
## FontsManager::get_FontFallBackRulesCollection() methode


Vertegenwoordigt de collectie van een gebruiker met FontFallBack-regels voor het beheren van collecties van lettertypen voor correcte vervangingen door fallback-functionaliteit. Lees [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> Aspose::Slides::FontsManager::get_FontFallBackRulesCollection() override
```

## Opmerkingen



```cpp
auto pres = MakeObject<Presentation>();
// Ophalen van een lege of vooraf geïnitialiseerde regels-collectie van FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// regels toevoegen aan de collectie
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// of
// initialisatie van een nieuwe instantie van de regels-collectie
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// regels toevoegen aan de collectie
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// en vervangen van de bestaande collectie door de nieuwe in FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Klasse [FontsManager](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)