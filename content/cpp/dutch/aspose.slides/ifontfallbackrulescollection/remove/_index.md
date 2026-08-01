---
title: Remove()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert de eerste instantie van een specifieke FallBack-regel uit de collectie.
type: docs
weight: 27
url: /nl/aspose.slides/ifontfallbackrulescollection/remove/
---
## IFontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) methode

Verwijdert de eerste instantie van een specifieke FallBack-regel uit de collectie.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | De regel die uit de collectie moet worden verwijderd. |
## Opmerkingen

```cpp
auto pres = MakeObject<Presentation>();
//Ophalen van lege of vooraf geïnitialiseerde regelsverzameling van FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Meerdere regels aan de collectie toevoegen
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Object van de eerste regel in de collectie ophalen
auto firstRule = rulesList->idx_get(0);
//Verwijderen
rulesList->Remove(firstRule);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IFontFallBackRule](../../ifontfallbackrule/)
* Klasse [IFontFallBackRulesCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)