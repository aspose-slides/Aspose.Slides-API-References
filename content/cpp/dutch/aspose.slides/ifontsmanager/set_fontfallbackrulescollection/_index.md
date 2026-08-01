---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een gebruikersverzameling van FontFallBack regels voor het beheren van verzamelingen lettertypen voor correcte substituties door fallback-functionaliteit. Schrijf IFontFallBackRulesCollection.
type: docs
weight: 40
url: /nl/aspose.slides/ifontsmanager/set_fontfallbackrulescollection/
---
## IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<IFontFallBackRulesCollection\>) methode


Stelt een gebruikersverzameling van FontFallBack regels voor voor het beheren van verzamelingen lettertypen voor juiste substituties door fallback functionaliteit Schrijf [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual void Aspose::Slides::IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr<IFontFallBackRulesCollection> value)=0
```

## Opmerkingen



```cpp
auto pres = MakeObject<Presentation>();
// Ophalen van lege of vooraf geïnitialiseerde regelsverzameling van FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// regels toevoegen aan verzameling
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// of
// initialisatie van nieuwe instantie van regelsverzameling
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// regels toevoegen aan verzameling
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// en vervangen van bestaande verzameling door de nieuwe in FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)