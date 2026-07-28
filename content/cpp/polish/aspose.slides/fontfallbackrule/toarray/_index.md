---
title: ToArray()
second_title: Aspose.Slides dla C++ - referencja API
description: Tworzy i zwraca tablicę ze wszystkimi czcionkami FallBack dla tej reguły.
type: docs
weight: 144
url: /pl/aspose.slides/fontfallbackrule/toarray/
---
## FontFallBackRule::ToArray() metoda


Tworzy i zwraca tablicę ze wszystkimi czcionkami FallBack dla tej reguły.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray() override
```


### Wartość zwracana

Tablica [System::String](../../../system/string/)
## Uwagi



```cpp
// Utwórz regułę zawierającą listę czcionek.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Pobierz wszystkie nazwy czcionek jako tablicę.
ArrayPtr<String> fontNames = newRule->ToArray();
```


## FontFallBackRule::ToArray(int32_t, int32_t) metoda


Tworzy i zwraca tablicę ze wszystkimi czcionkami FallBack z określonego zakresu na liście.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray(int32_t startIndex, int32_t count) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| startIndex | **int32_t** | Indeks pierwszej czcionki do dodania. |
| count | **int32_t** | Liczba czcionek do dodania. |

### Wartość zwracana

Tablica [System::String](../../../system/string/)
## Uwagi



```cpp
// Utwórz regułę zawierającą listę czcionek.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Pobierz dwie ostatnie nazwy czcionek jako tablicę.
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```


## Zobacz także

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [String](../../../system/string/)
* Klasa [FontFallBackRule](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)