---
title: Compare()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Porównuje dwa podciągi, zwracając wartość mniejszą, równą lub większą.
type: docs
weight: 820
url: /pl/system/string/compare/
---
## String::Compare(const String\&, int, const String\&, int, int, bool) metoda


Porównuje dwa podciągi, zwracając wartość mniejszą, równą lub większą.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase=false)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| strA | const [String](../)\& | Pierwszy ciąg do porównania. |
| indexA | int | Początek podciągu pierwszego ciągu. |
| strB | const [String](../)\& | Drugi ciąg do porównania. |
| indexB | int | Początek podciągu drugiego ciągu. |
| length | int | Liczba znaków do porównania. |
| ignoreCase | **bool** | Określa, czy porównanie jest niewrażliwe na wielkość liter. |

### Wartość zwracana

Ujemna wartość, jeśli pierwszy podciąg jest mniejszy od drugiego, zero, jeśli są równe, dodatnia wartość w przeciwnym razie.

## String::Compare(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) metoda


Porównuje dwa podciągi, zwracając wartość mniejszą, równą lub większą.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| strA | const [String](../)\& | Pierwszy ciąg do porównania. |
| indexA | int | Początek podciągu pierwszego ciągu. |
| strB | const [String](../)\& | Drugi ciąg do porównania. |
| indexB | int | Początek podciągu drugiego ciągu. |
| length | int | Liczba znaków do porównania. |
| ignoreCase | **bool** | Określa, czy porównanie jest niewrażliwe na wielkość liter. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultura używana do porównania. |

### Wartość zwracana

Ujemna wartość, jeśli pierwszy podciąg jest mniejszy od drugiego, zero, jeśli są równe, dodatnia wartość w przeciwnym razie.

## String::Compare(const String\&, const String\&, System::StringComparison) metoda


Porównuje dwa ciągi znaków, zwracając wartość mniejszą, równą lub większą.

```cpp
static int System::String::Compare(const String &strA, const String &strB, System::StringComparison comparison_type)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| strA | const [String](../)\& | Pierwszy ciąg do porównania. |
| strB | const [String](../)\& | Drugi ciąg do porównania. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | Tryb [Comparison](../../comparison/). |

### Wartość zwracana

Ujemna wartość, jeśli pierwszy ciąg jest mniejszy od drugiego, zero, jeśli są równe, dodatnia wartość w przeciwnym razie.

## String::Compare(const String\&, int, const String\&, int, int, System::StringComparison) metoda


Porównuje dwa ciągi znaków, zwracając wartość mniejszą, równą lub większą.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, System::StringComparison comparison_type)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| strA | const [String](../)\& | Pierwszy ciąg do porównania. |
| indexA | int | Początek podciągu pierwszego ciągu. |
| strB | const [String](../)\& | Drugi ciąg do porównania. |
| indexB | int | Początek podciągu drugiego ciągu. |
| length | int | Liczba znaków do porównania. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | Tryb [Comparison](../../comparison/). |

### Wartość zwracana

Ujemna wartość, jeśli pierwszy ciąg jest mniejszy od drugiego, zero, jeśli są równe, dodatnia wartość w przeciwnym razie.

## String::Compare(const String\&, const String\&, bool) metoda


Porównuje dwa ciągi znaków, zwracając wartość mniejszą, równą lub większą.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase=false)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| strA | const [String](../)\& | Pierwszy ciąg do porównania. |
| strB | const [String](../)\& | Drugi ciąg do porównania. |
| ignoreCase | **bool** | Określa, czy porównanie jest niewrażliwe na wielkość liter. |

### Wartość zwracana

Ujemna wartość, jeśli pierwszy ciąg jest mniejszy od drugiego, zero, jeśli są równe, dodatnia wartość w przeciwnym razie.

## String::Compare(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) metoda


Porównuje dwa ciągi znaków, zwracając wartość mniejszą, równą lub większą.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| strA | const [String](../)\& | Pierwszy ciąg do porównania. |
| strB | const [String](../)\& | Drugi ciąg do porównania. |
| ignoreCase | **bool** | Określa, czy porównanie jest niewrażliwe na wielkość liter. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultura używana do porównania. |

### Wartość zwracana

Ujemna wartość, jeśli pierwszy ciąg jest mniejszy od drugiego, zero, jeśli są równe, dodatnia wartość w przeciwnym razie.

## Zobacz także

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasa [String](../)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Przestrzeń nazw [System](../../)
* Library [Aspose.Slides](../../../)