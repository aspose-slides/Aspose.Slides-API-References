---
title: IndexOf()
second_title: Aspose.Slides pro C++ reference API
description: Vrací index zadaného pravidla ve sbírce.
type: docs
weight: 118
url: /cs/aspose.slides/ifontfallbackrule/indexof/
---
## IFontFallBackRule::IndexOf(System::String) metoda


Vrátí index určeného pravidla ve sbírce.

```cpp
virtual int32_t Aspose::Slides::IFontFallBackRule::IndexOf(System::String fontName)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Název písma, které se má najít. |

### Návratová hodnota

Index písma nebo -1, pokud písmo není v seznamu nalezeno.
## Poznámky



```cpp
// Vytvoří pravidlo obsahující seznam písem.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Získá index písma Tahoma
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```


## Viz také

* Třída [String](../../../system/string/)
* Třída [IFontFallBackRule](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)