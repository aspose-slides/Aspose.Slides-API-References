---
title: Add()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een opgegeven FallBack-regel toe aan het einde van de collectie.
type: docs
weight: 40
url: /nl/aspose.slides/fontfallbackrulescollection/add/
---
## FontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) methode


Voegt een opgegeven FallBack-regel toe aan het einde van de collectie.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Opgegeven regel voor toevoegen |
## Opmerkingen



```cpp
auto pres = MakeObject<Presentation>();
//Opvragen van lege of voorgeïnitieerde regelsverzameling van FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Toevoegen van nieuwe regel aan collectie
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```


## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IFontFallBackRule](../../ifontfallbackrule/)
* Klasse [FontFallBackRulesCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)