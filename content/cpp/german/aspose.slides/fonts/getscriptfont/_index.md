---
title: GetScriptFont()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft den Schriftartnamen ab, der mit einem bestimmten Skript-Tag aus dem Präsentationsthema verknüpft ist.
type: docs
weight: 92
url: /de/aspose.slides/fonts/getscriptfont/
---
## Fonts::GetScriptFont(System::String) Methode

Ruft den Schriftartnamen ab, der mit einem bestimmten Skript-Tag aus dem Präsentationsthema verknüpft ist.

```cpp
System::String Aspose::Slides::Fonts::GetScriptFont(System::String script) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Der BCP-47-Skriptcode (z. B. "Latn", "Cyrl", "Jpan"), der zur Identifizierung eines Schriftsystems verwendet wird. |

### Rückgabewert

Der Name der für das angegebene Skript verwendeten Schriftart oder **null**, falls das Skript nicht definiert ist.

## Bemerkungen

Dieses Beispiel zeigt, wie die dem kyrillischen Skript zugewiesene Schriftart im Präsentationsthema abgerufen wird.
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [Fonts](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)