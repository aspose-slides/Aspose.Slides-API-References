---
title: Remove()
second_title: Aspose.Slides für C++ API Referenz
description: Entfernt das erste Vorkommen einer bestimmten FallBack-Schriftart aus der Liste.
type: docs
weight: 118
url: /de/aspose.slides/fontfallbackrule/remove/
---
## FontFallBackRule::Remove(System::String) Methode

Entfernt das erste Vorkommen einer bestimmten FallBack-Schriftart aus der Liste.

```cpp
void Aspose::Slides::FontFallBackRule::Remove(System::String fontName) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Der Name der Schriftart, die aus der Liste entfernt werden soll. |

## Anmerkungen

```cpp
// Erstelle eine Regel, die eine Liste von Schriftarten enthält.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Entferne Tahoma aus der Liste.
newRule->Remove(u"Tahoma");
```

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [FontFallBackRule](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)