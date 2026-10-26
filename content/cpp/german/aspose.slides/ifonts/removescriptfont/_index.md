---
title: RemoveScriptFont()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt die mit einem bestimmten Skript-Tag verbundene Schriftarteinstellung aus der Schriftartsammlung des Themes.
type: docs
weight: 118
url: /de/aspose.slides/ifonts/removescriptfont/
---
## IFonts::RemoveScriptFont(System::String) Methode

Entfernt die mit einem bestimmten Skript-Tag verknüpfte Schriftarteinstellung aus der Schriftartsammlung des Themes.

```cpp
virtual void Aspose::Slides::IFonts::RemoveScriptFont(System::String script)=0
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Der BCP-47 Skriptcode, dessen Schriftarteinstellung entfernt werden soll. |
## Anmerkungen

Dieses Beispiel zeigt, wie die Schriftartzuordnung für das hebräische Skript entfernt wird: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [IFonts](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)