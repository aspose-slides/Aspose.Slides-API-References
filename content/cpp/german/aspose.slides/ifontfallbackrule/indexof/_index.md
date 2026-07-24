---
title: IndexOf()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt einen Index der angegebenen Regel in der Sammlung zurück.
type: docs
weight: 118
url: /de/aspose.slides/ifontfallbackrule/indexof/
---
## IFontFallBackRule::IndexOf(System::String) Methode


Gibt einen Index der angegebenen Regel in der Sammlung zurück.

```cpp
virtual int32_t Aspose::Slides::IFontFallBackRule::IndexOf(System::String fontName)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Name der zu findenden Schriftart. |

### Rückgabewert

Index einer Schriftart oder -1, wenn die Schriftart nicht in der Liste gefunden wurde.
## Hinweise



```cpp
// Erstelle eine Regel, die eine Liste von Schriftarten enthält.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Hole den Index von Tahoma
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```


## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [IFontFallBackRule](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)