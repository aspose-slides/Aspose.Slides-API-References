---
title: IndexOf()
second_title: Aspose.Slides pro C++ - reference API
description: Vrací index určeného pravidla v kolekci.
type: docs
weight: 157
url: /cs/aspose.slides/fontfallbackrule/indexof/
---
## FontFallBackRule::IndexOf(System::String) metoda


Vrací index určeného pravidla v kolekci.

```cpp
int32_t Aspose::Slides::FontFallBackRule::IndexOf(System::String fontName) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Název písma k vyhledání. |

### Návratová hodnota

Index písma nebo -1, pokud písmo není v seznamu.
## Poznámky



```cpp
// Vytvoří pravidlo, které obsahuje seznam fontů.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Získá index Tahoma.
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```


## Viz také

* Třída [String](../../../system/string/)
* Třída [FontFallBackRule](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)