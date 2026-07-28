---
title: IndexOf()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca indeks określonej reguły w kolekcji.
type: docs
weight: 118
url: /pl/aspose.slides/ifontfallbackrule/indexof/
---
## IFontFallBackRule::IndexOf(System::String) metoda


Zwraca indeks określonej reguły w kolekcji.

```cpp
virtual int32_t Aspose::Slides::IFontFallBackRule::IndexOf(System::String fontName)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Nazwa czcionki do znalezienia. |

### Wartość zwracana

Indeks czcionki lub -1, jeśli czcionka nie została znaleziona na liście.
## Uwagi



```cpp
// Utwórz regułę zawierającą listę czcionek.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Pobierz indeks Tahoma
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```


## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [IFontFallBackRule](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)