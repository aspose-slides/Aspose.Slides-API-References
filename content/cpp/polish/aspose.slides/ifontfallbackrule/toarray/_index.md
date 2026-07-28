---
title: ToArray()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Tworzy i zwraca tablicę ze wszystkimi czcionkami zastępczymi dla tej reguły.
type: docs
weight: 105
url: /pl/aspose.slides/ifontfallbackrule/toarray/
---
## IFontFallBackRule::ToArray() metoda


Tworzy i zwraca tablicę ze wszystkimi czcionkami zastępczymi dla tej reguły.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray()=0
```


### Wartość zwracana

Tablica [System::String](../../../system/string/)
## Uwagi



```cpp
// Utwórz regułę zawierającą listę czcionek.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Pobierz wszystkie nazwy czcionek jako tablicę
ArrayPtr<String> fontNames = newRule->ToArray();
```


## IFontFallBackRule::ToArray(int32_t, int32_t) metoda


Tworzy i zwraca tablicę ze wszystkimi czcionkami zastępczymi z określonego zakresu na liście.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray(int32_t startIndex, int32_t count)=0
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
//Pobierz dwie ostatnie nazwy czcionek jako tablicę
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```


## Zobacz też

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [String](../../../system/string/)
* Klasa [IFontFallBackRule](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)