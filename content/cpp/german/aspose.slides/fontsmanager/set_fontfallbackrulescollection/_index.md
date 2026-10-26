---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides für C++ API Referenz
description: Stellt die Sammlung von FontFallBack-Regeln eines Benutzers zur Verwaltung von Schriftartensammlungen für korrekte Ersetzungen durch die Fallback-Funktionalität bereit. Schreiben IFontFallBackRulesCollection.
type: docs
weight: 40
url: /de/aspose.slides/fontsmanager/set_fontfallbackrulescollection/
---
## FontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<Aspose::Slides::IFontFallBackRulesCollection\>) Methode

Stellt die Sammlung von FontFallBack-Regeln eines Benutzers zur Verwaltung von Schriftartensammlungen für korrekte Ersetzungen durch die Fallback-Funktionalität bereit. Schreiben [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
void Aspose::Slides::FontsManager::set_FontFallBackRulesCollection(System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> value) override
```

## Bemerkungen

```cpp
auto pres = MakeObject<Presentation>();
// Abrufen einer leeren oder vorinitialisierten Regelensammlung von FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// Hinzufügen von Regeln zur Sammlung
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// oder
// Initialisierung einer neuen Instanz der Regelensammlung
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// Hinzufügen von Regeln zur Sammlung
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// und Ersetzen der vorhandenen Sammlung durch die neue in FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Klasse [FontsManager](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)