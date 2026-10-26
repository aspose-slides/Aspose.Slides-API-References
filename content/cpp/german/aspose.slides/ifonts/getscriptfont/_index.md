---
title: GetScriptFont()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt den Schriftartnamen, der mit einem bestimmten Skript-Tag aus dem Präsentationsthema verknüpft ist.
type: docs
weight: 92
url: /de/aspose.slides/ifonts/getscriptfont/
---
## IFonts::GetScriptFont(System::String) Methode

Ruft den Namen der Schriftart ab, die mit einem bestimmten Skript-Tag aus dem Präsentationsthema verknüpft ist.

```cpp
virtual System::String Aspose::Slides::IFonts::GetScriptFont(System::String script)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Der BCP-47-Skriptcode (z. B. "Latn", "Cyrl", "Jpan"), der zur Identifizierung eines Schriftsystems verwendet wird. |

### Rückgabewert

Der Name der für das angegebene Skript verwendeten Schriftart oder **null**, wenn das Skript nicht definiert ist.

## Bemerkungen

Dieses Beispiel zeigt, wie die dem kyrillischen Skript zugewiesene Schriftart im Präsentationsthema abgerufen wird.
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## Siehe Auch

* Klasse [String](../../../system/string/)
* Klasse [IFonts](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)