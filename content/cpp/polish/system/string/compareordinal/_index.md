---
title: CompareOrdinal()
second_title: Aspose.Slides dla API C++
description: Porównuje dwa ciągi znaków w trybie porządkowym, zwracając wartość mniejszą, równą lub większą.
type: docs
weight: 833
url: /pl/system/string/compareordinal/
---
## String::CompareOrdinal(const String&, const String&) metoda

Porównuje dwa ciągi znaków w trybie porządkowym, zwracając wartość mniejszą, równą lub większą.

```cpp
static int System::String::CompareOrdinal(const String &strA, const String &strB)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| strA | const [String](../)\& | Pierwszy ciąg do porównania. |
| strB | const [String](../)\& | Drugi ciąg do porównania. |

### Wartość zwracana

Ujemna wartość, jeśli pierwszy podciąg jest mniejszy niż drugi, zero, jeśli są równe, dodatnia wartość w przeciwnym wypadku.

## String::CompareOrdinal(const String&, int, const String&, int, int) metoda

Porównuje dwa ciągi znaków w trybie porządkowym, zwracając wartość mniejszą, równą lub większą.

```cpp
static int System::String::CompareOrdinal(const String &strA, int indexA, const String &strB, int indexB, int length)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| strA | const [String](../)\& | Pierwszy ciąg do porównania. |
| indexA | int | Początek pierwszego podciągu ciągu znaków. |
| strB | const [String](../)\& | Drugi ciąg do porównania. |
| indexB | int | Początek drugiego podciągu ciągu znaków. |
| length | int | Liczba znaków do porównania. |

### Wartość zwracana

Ujemna wartość, jeśli pierwszy podciąg jest mniejszy niż drugi, zero, jeśli są równe, dodatnia wartość w przeciwnym wypadku.

## Zobacz także

* Klasa [String](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)