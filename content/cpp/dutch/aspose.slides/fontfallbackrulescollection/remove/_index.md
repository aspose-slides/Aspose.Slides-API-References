---
title: Remove()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert het eerste voorkomen van een specifieke FallBack regel uit de collectie.
type: docs
weight: 53
url: /nl/aspose.slides/fontfallbackrulescollection/remove/
---
## FontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) methode

Verwijdert het eerste voorkomen van een specifieke FallBack regel uit de collectie.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | De regel die uit de collectie moet worden verwijderd. |
## Opmerkingen



```cpp
auto pres = MakeObject<Presentation>();
//Ophalen van lege of vooraf geïnitialiseerde regelscollectie van FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Toevoegen van meerdere regels aan de collectie
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Ophalen van object van de eerste regel in de collectie
auto firstRule = rulesList->idx_get(0);
//Verwijderen
rulesList->Remove(firstRule);
```


## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IFontFallBackRule](../../ifontfallbackrule/)
* Klasse [FontFallBackRulesCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)