---
title: Add()
second_title: Aspose.Slides für C++ API Referenz
description: Fügt eine angegebene FallBack-Regel am Ende der Sammlung hinzu.
type: docs
weight: 40
url: /de/aspose.slides/fontfallbackrulescollection/add/
---
## FontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) method

Fügt eine angegebene FallBack-Regel am Ende der Sammlung hinzu.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Angegebene Regel zum Hinzufügen |
## Hinweise

```cpp
auto pres = MakeObject<Presentation>();
//Abrufen einer leeren oder vorinitialisierten Regel-Sammlung aus dem FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Hinzufügen einer neuen Regel zur Sammlung
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IFontFallBackRule](../../ifontfallbackrule/)
* Klasse [FontFallBackRulesCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)