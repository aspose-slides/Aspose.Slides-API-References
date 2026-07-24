---
title: SetScriptFont()
second_title: Aspose.Slides für C++ API-Referenz
description: Weist einem bestimmten Skript-Tag einen Schriftartnamen zu, der definiert, wie Text dieses Skripts in der Präsentation gerendert wird.
type: docs
weight: 105
url: /de/aspose.slides/ifonts/setscriptfont/
---
## IFonts::SetScriptFont(System::String, System::String) Methode

Weist einem bestimmten Skript-Tag einen Schriftartnamen zu, der definiert, wie Text dieses Skripts in der Präsentation gerendert wird.

```cpp
virtual void Aspose::Slides::IFonts::SetScriptFont(System::String script, System::String fontName)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Der BCP-47-Skriptcode (z. B. "Arab", "Hebr", "Hans"), der das Schriftsystem identifiziert. |
| fontName | [System::String](../../../system/string/) | Der Name der Schriftart, die dem angegebenen Skript zugewiesen werden soll. |

## Bemerkungen

Dieses Beispiel zeigt, wie die Schriftart für das arabische Skript auf "Segoe UI" gesetzt wird:
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [IFonts](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)