---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een gebruikersverzameling van FontFallBack-regels voor het beheren van collecties van lettertypen voor correcte vervangingen door fallback-functionaliteit. Lees IFontFallBackRulesCollection.
type: docs
weight: 27
url: /nl/aspose.slides/ifontsmanager/get_fontfallbackrulescollection/
---
## IFontsManager::get_FontFallBackRulesCollection() methode


Stelt een gebruikersverzameling van FontFallBack-regels voor voor het beheren van collecties van lettertypen voor correcte vervangingen door fallback-functionaliteit. Lees [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual System::SharedPtr<IFontFallBackRulesCollection> Aspose::Slides::IFontsManager::get_FontFallBackRulesCollection()=0
```

## Opmerkingen



```cpp
auto pres = MakeObject<Presentation>();
// Ophalen van een lege of vooraf geïnitialiseerde regelsverzameling van FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// toevoegen van regels aan de verzameling
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// of
// initialisatie van een nieuw exemplaar van de regelsverzameling
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// toevoegen van regels aan de verzameling
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// en vervangen van de bestaande verzameling door de nieuwe in FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Klasse [IFontsManager](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)