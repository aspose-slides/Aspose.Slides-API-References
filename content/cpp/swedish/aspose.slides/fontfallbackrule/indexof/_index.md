---
title: IndexOf()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ett index för den angivna regeln i samlingen.
type: docs
weight: 157
url: /sv/aspose.slides/fontfallbackrule/indexof/
---
## FontFallBackRule::IndexOf(System::String) metod

Returnerar ett index för den angivna regeln i samlingen.

```cpp
int32_t Aspose::Slides::FontFallBackRule::IndexOf(System::String fontName) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Fontens namn att hitta. |

### Returvärde

Index för ett typsnitt eller -1 om typsnittet inte hittas i listan.

## Anmärkningar

```cpp
// Skapa en regel som innehåller en lista med fonter.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Hämta index för Tahoma.
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```

## Se också

* Klass [String](../../../system/string/)
* Klass [FontFallBackRule](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)