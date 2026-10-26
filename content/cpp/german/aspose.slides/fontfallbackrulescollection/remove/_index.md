---
title: Remove()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt das erste Vorkommen einer bestimmten FallBack-Regel aus der Sammlung.
type: docs
weight: 53
url: /de/aspose.slides/fontfallbackrulescollection/remove/
---
## FontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) method

Entfernt das erste Vorkommen einer bestimmten FallBack-Regel aus der Sammlung.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule) override
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Die Regel, die aus der Sammlung entfernt werden soll. |
## Remarks

```cpp
auto pres = MakeObject<Presentation>();
//Abrufen einer leeren oder vorinitialisierten Regelsammlung vom FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Hinzufügen mehrerer Regeln zur Sammlung
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Abrufen des Objekts der ersten Regel in der Sammlung
auto firstRule = rulesList->idx_get(0);
//Entfernen
rulesList->Remove(firstRule);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IFontFallBackRule](../../ifontfallbackrule/)
* Klasse [FontFallBackRulesCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)