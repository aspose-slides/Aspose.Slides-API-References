---
title: IndexOf()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca indeks określonej reguły w kolekcji.
type: docs
weight: 157
url: /pl/aspose.slides/fontfallbackrule/indexof/
---
## FontFallBackRule::IndexOf(System::String) method


Zwraca indeks określonej reguły w kolekcji.

```cpp
int32_t Aspose::Slides::FontFallBackRule::IndexOf(System::String fontName) override
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
// Pobierz indeks czcionki Tahoma.
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```


## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [FontFallBackRule](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)