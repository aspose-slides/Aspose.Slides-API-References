---
title: RemoveScriptFont()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt die Schriftarteinstellung, die mit einem bestimmten Skript-Tag verknüpft ist, aus der Schriftartensammlung des Themas.
type: docs
weight: 118
url: /de/aspose.slides/fonts/removescriptfont/
---
## Fonts::RemoveScriptFont(System::String) Methode

Entfernt die Schriftarteinstellung, die mit einem bestimmten Skript-Tag verknüpft ist, aus der Schriftartensammlung des Themas.

```cpp
void Aspose::Slides::Fonts::RemoveScriptFont(System::String script) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Der BCP-47-Skriptcode, dessen Schriftarteinstellung entfernt werden soll. |
## Hinweise

Dieses Beispiel zeigt, wie die Schriftartenzuordnung für das hebräische Skript entfernt wird: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [Fonts](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)