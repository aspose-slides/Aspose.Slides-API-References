---
title: IndexOf()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ett index för den angivna regeln i samlingen.
type: docs
weight: 118
url: /sv/aspose.slides/ifontfallbackrule/indexof/
---
## IFontFallBackRule::IndexOf(System::String) metod

Returnerar ett index för den angivna regeln i samlingen.

```cpp
virtual int32_t Aspose::Slides::IFontFallBackRule::IndexOf(System::String fontName)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Fontens namn att hitta. |

### Returvärde

Index för ett teckensnitt eller -1 om teckensnittet inte finns i listan.

## Anmärkningar

```cpp
// Skapa en regel som innehåller en lista med typsnitt.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Hämta index för Tahoma
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```

## Se även

* Klass [String](../../../system/string/)
* Klass [IFontFallBackRule](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)