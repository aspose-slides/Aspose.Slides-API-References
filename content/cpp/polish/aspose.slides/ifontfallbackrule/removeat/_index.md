---
title: RemoveAt()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Usuwa czcionkę FallBack pod wskazanym indeksem w liście.
type: docs
weight: 92
url: /pl/aspose.slides/ifontfallbackrule/removeat/
---
## IFontFallBackRule::RemoveAt(int32_t) metoda

Usuwa czcionkę FallBack pod wskazanym indeksem na liście.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::RemoveAt(int32_t index)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy czcionki do usunięcia. |

## Uwagi

```cpp
// Utwórz regułę zawierającą listę czcionek.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Usuwanie czcionki Tahoma z listy
newRule->RemoveAt(2);
```

## Zobacz także

* Klasa [IFontFallBackRule](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)