---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides voor C++ API-referentie
description: Vertegenwoordigt een gebruikerscollectie van FontFallBack regels voor het beheren van verzamelingen lettertypen voor correcte substituties via fallback-functionaliteit Schrijf IFontFallBackRulesCollection.
type: docs
weight: 40
url: /nl/aspose.slides/fontsmanager/set_fontfallbackrulescollection/
---
## FontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<Aspose::Slides::IFontFallBackRulesCollection\>) method

Vertegenwoordigt een verzameling FontFallBack-regels van de gebruiker voor het beheren van verzamelingen lettertypen voor correcte substituties via fallback-functionaliteit Schrijf [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
void Aspose::Slides::FontsManager::set_FontFallBackRulesCollection(System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> value) override
```

## Opmerkingen



```cpp
auto pres = MakeObject<Presentation>();
// Lezen van lege of vooraf geïnitialiseerde regelsverzameling van FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// toevoegen van regels aan de verzameling
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// of
// initialisatie van een nieuwe instantie van de regelsverzameling
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// toevoegen van regels aan de verzameling
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// en vervangen van de bestaande verzameling door de nieuwe in FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Klasse [FontsManager](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)