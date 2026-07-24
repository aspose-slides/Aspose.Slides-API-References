---
title: idx_get()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt die Regel am angegebenen Index. Nur Lesezugriff IFontFallBackRule.
type: docs
weight: 66
url: /de/aspose.slides/fontfallbackrulescollection/idx_get/
---
## FontFallBackRulesCollection::idx_get(int32_t) Methode


Ermittelt die Regel am angegebenen Index. Nur Lesezugriff [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
System::SharedPtr<IFontFallBackRule> Aspose::Slides::FontFallBackRulesCollection::idx_get(int32_t index) override
```

## Anmerkungen



```cpp
auto pres = MakeObject<Presentation>();
//Abrufen einer leeren oder vorinitialisierten Regel-Sammlung vom FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Hinzufügen mehrerer Regeln zur Sammlung
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Abrufen des Objekts der ersten Regel in der Sammlung
auto firstRule = rulesList->idx_get(0);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IFontFallBackRule](../../ifontfallbackrule/)
* Klasse [FontFallBackRulesCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)