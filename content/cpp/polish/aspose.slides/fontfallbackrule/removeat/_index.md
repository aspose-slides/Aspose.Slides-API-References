---
title: RemoveAt()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Usuwa czcionkę fallback pod wskazanym indeksem listy.
type: docs
weight: 131
url: /pl/aspose.slides/fontfallbackrule/removeat/
---
## FontFallBackRule::RemoveAt(int32_t) metoda


Usuwa czcionkę fallback pod wskazanym indeksem listy.

```cpp
void Aspose::Slides::FontFallBackRule::RemoveAt(int32_t index) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy czcionki do usunięcia. |
## Uwagi



```cpp
// Utwórz regułę zawierającą listę czcionek.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Usuwanie Tahoma z listy.
newRule->RemoveAt(2);
```


## Zobacz także

* Klasa [FontFallBackRule](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)