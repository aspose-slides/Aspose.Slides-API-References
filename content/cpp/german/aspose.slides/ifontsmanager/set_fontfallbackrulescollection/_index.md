---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt die Sammlung von FontFallBack-Regeln eines Benutzers dar, die zur Verwaltung von Schriftartensammlungen für korrekte Ersetzungen durch die Fallback-Funktionalität verwendet werden. Schreiben IFontFallBackRulesCollection.
type: docs
weight: 40
url: /de/aspose.slides/ifontsmanager/set_fontfallbackrulescollection/
---
## IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<IFontFallBackRulesCollection\>) Methode

Stellt die Sammlungen von FontFallBack-Regeln eines Benutzers dar, die zur Verwaltung von Schriftartensammlungen für korrekte Ersetzungen durch die Fallback-Funktionalität verwendet werden. Schreiben [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual void Aspose::Slides::IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr<IFontFallBackRulesCollection> value)=0
```

## Hinweise

```cpp
auto pres = MakeObject<Presentation>();
// Abrufen einer leeren oder vorinitialisierten Regelsammlung vom FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// Hinzufügen von Regeln zur Sammlung
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// oder
// Initialisierung einer neuen Instanz der Regelsammlung
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// Hinzufügen von Regeln zur Sammlung
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// und Ersetzen der vorhandenen Sammlung durch die neue im FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Klasse [IFontsManager](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)