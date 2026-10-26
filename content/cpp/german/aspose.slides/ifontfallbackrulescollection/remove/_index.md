---
title: Remove()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt das erste Vorkommen einer bestimmten FallBack-Regel aus der Sammlung.
type: docs
weight: 27
url: /de/aspose.slides/ifontfallbackrulescollection/remove/
---
## IFontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) Methode


Entfernt das erste Vorkommen einer bestimmten FallBack-Regel aus der Sammlung.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Die Regel, die aus der Sammlung entfernt werden soll. |
## Bemerkungen



```cpp
auto pres = MakeObject<Presentation>();
//Abrufen einer leeren oder vorinitialisierten Regelensammlung vom FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Hinzufügen mehrerer Regeln zur Sammlung
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Abrufen des Objekts der ersten Regel in der Sammlung
auto firstRule = rulesList->idx_get(0);
//Entfernen
rulesList->Remove(firstRule);
```


## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IFontFallBackRule](../../ifontfallbackrule/)
* Klasse [IFontFallBackRulesCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)