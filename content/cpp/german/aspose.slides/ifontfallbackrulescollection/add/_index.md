---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt eine neue FallBack-Regel am Ende der Sammlung hinzu.
type: docs
weight: 14
url: /de/aspose.slides/ifontfallbackrulescollection/add/
---
## IFontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) Methode

Fügt eine neue FallBack-Regel am Ende der Sammlung hinzu.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Angegebene Regel zum Hinzufügen |
## Hinweise



```cpp
auto pres = MakeObject<Presentation>();
//Abrufen einer leeren oder vorinitialisierten Regel-Sammlung vom FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Hinzufügen einer neuen Regel zur Sammlung
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IFontFallBackRule](../../ifontfallbackrule/)
* Klasse [IFontFallBackRulesCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)