---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt eine Benutzersammlung von FontFallBack-Regeln für die Verwaltung von Sammlungen von Schriftarten für korrekte Ersetzungen durch die Fallback-Funktionalität dar. Lesen IFontFallBackRulesCollection.
type: docs
weight: 27
url: /de/aspose.slides/fontsmanager/get_fontfallbackrulescollection/
---
## FontsManager::get_FontFallBackRulesCollection() Methode


Stellt eine Benutzersammlung von FontFallBack-Regeln für die Verwaltung von Sammlungen von Schriftarten für korrekte Ersetzungen durch die Fallback-Funktionalität dar. Lesen [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> Aspose::Slides::FontsManager::get_FontFallBackRulesCollection() override
```

## Anmerkungen



```cpp
auto pres = MakeObject<Presentation>();
// Abrufen einer leeren oder vorinitialisierten Regel-Sammlung vom FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// Hinzufügen von Regeln zur Sammlung
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// oder
// Initialisierung einer neuen Instanz der Regel-Sammlung
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// Hinzufügen von Regeln zur Sammlung
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// und Ersetzen der bestehenden Sammlung durch die neue im FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Klasse [FontsManager](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)