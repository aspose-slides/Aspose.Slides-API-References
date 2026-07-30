---
title: CompareOrdinal()
second_title: Aspose.Slides pro C++ – dokumentace API
description: Porovnává dva řetězce pomocí ordinálního režimu (menší-rovná-větší).
type: docs
weight: 833
url: /cs/system/string/compareordinal/
---
## String::CompareOrdinal(const String\&, const String\&) metoda

Porovnává dva řetězce pomocí ordinálního režimu (menší-rovná-větší).

```cpp
static int System::String::CompareOrdinal(const String &strA, const String &strB)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| strA | const [String](../)\& | První řetězec k porovnání. |
| strB | const [String](../)\& | Druhý řetězec k porovnání. |

### Návratová hodnota

Záporná hodnota, pokud je první podřetězec menší než druhý, nula, pokud se shodují, kladná hodnota v opačném případě.

## String::CompareOrdinal(const String\&, int, const String\&, int, int) metoda

Porovnává dva řetězce pomocí ordinálního režimu (menší-rovná-větší).

```cpp
static int System::String::CompareOrdinal(const String &strA, int indexA, const String &strB, int indexB, int length)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| strA | const [String](../)\& | První řetězec k porovnání. |
| indexA | int | Začátek podřetězce prvního řetězce. |
| strB | const [String](../)\& | Druhý řetězec k porovnání. |
| indexB | int | Začátek podřetězce druhého řetězce. |
| length | int | Počet znaků k porovnání. |

### Návratová hodnota

Záporná hodnota, pokud je první podřetězec menší než druhý, nula, pokud se shodují, kladná hodnota v opačném případě.

## Viz také

* Třída [String](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)