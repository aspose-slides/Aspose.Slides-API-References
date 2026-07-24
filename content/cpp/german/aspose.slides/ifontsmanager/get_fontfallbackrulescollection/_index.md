---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt die Sammlung von FontFallBack-Regeln eines Benutzers dar, um Sammlungen von Schriftarten für korrekte Ersetzungen durch die Fallback-Funktionalität zu verwalten. Lesen IFontFallBackRulesCollection.
type: docs
weight: 27
url: /de/aspose.slides/ifontsmanager/get_fontfallbackrulescollection/
---
## IFontsManager::get_FontFallBackRulesCollection() Methode


Stellt die Sammlung von FontFallBack-Regeln eines Benutzers dar, um Sammlungen von Schriftarten für korrekte Ersetzungen durch die Fallback-Funktionalität zu verwalten. Lesen Sie [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual System::SharedPtr<IFontFallBackRulesCollection> Aspose::Slides::IFontsManager::get_FontFallBackRulesCollection()=0
```

## Anmerkungen



```cpp
auto pres = MakeObject<Presentation>();
// Abrufen einer leeren oder vorinitialisierten Regelensammlung aus dem FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// Hinzufügen von Regeln zur Sammlung
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// oder
// Initialisierung einer neuen Instanz der Regelensammlung
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// Hinzufügen von Regeln zur Sammlung
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// und Ersetzen der bestehenden Sammlung durch die neue im FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Klasse [IFontsManager](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)