---
title: Add()
second_title: Aspose.Slides voor C++ API-referentie
description: Voeg een nieuwe FallBack-regel toe aan het einde van de verzameling.
type: docs
weight: 14
url: /nl/aspose.slides/ifontfallbackrulescollection/add/
---
## IFontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) methode

Voegt een nieuwe FallBack-regel toe aan het einde van de collectie.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Gespecificeerde regel voor het toevoegen |
## Opmerkingen

```cpp
auto pres = MakeObject<Presentation>();
//Ophalen van een lege of vooraf geïnitialiseerde regelscollectie van FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Toevoegen van een nieuwe regel aan de collectie
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IFontFallBackRule](../../ifontfallbackrule/)
* Klasse [IFontFallBackRulesCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)