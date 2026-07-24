---
title: IndexOf()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt einen Index der angegebenen Regel in der Sammlung zurück.
type: docs
weight: 157
url: /de/aspose.slides/fontfallbackrule/indexof/
---
## FontFallBackRule::IndexOf(System::String) method

Returns an index of the specified rule in the collection.

```cpp
int32_t Aspose::Slides::FontFallBackRule::IndexOf(System::String fontName) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Name der zu findenden Schriftart. |

### Rückgabewert

Index einer Schriftart oder -1, falls die Schriftart nicht in der Liste gefunden wurde.

## Bemerkungen

```cpp
// Erstelle eine Regel, die eine Liste von Schriftarten enthält.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Erhalte den Index von Tahoma.
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [FontFallBackRule](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)