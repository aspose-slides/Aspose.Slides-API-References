---
title: IndexOf()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Wyszukiwanie podciągu w przód.
type: docs
weight: 625
url: /pl/system/string/indexof/
---
## String::IndexOf(const String\&, System::StringComparison) const metoda


Substring forward lookup.

```cpp
int System::String::IndexOf(const String &str, System::StringComparison comparison_type) const
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Podciąg do wyszukania. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) tryb. |

### Wartość zwracana

[Index](../../index/) pierwszego znalezionego podciągu lub -1, jeśli nie znaleziono. Dla pustego ciągu wyszukiwania zawsze zwraca 0.

## String::IndexOf(char_t, int) const metoda


Character forward lookup.

```cpp
int System::String::IndexOf(char_t c, int startIndex=0) const
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | Znak do wyszukania. |
| startIndex | int | [Index](../../index/) do rozpoczęcia wyszukiwania. |

### Wartość zwracana

[Index](../../index/) pierwszej pozycji znaku od startIndex lub -1, jeśli nie znaleziono.

## String::IndexOf(char_t, int, int) const metoda


Character forward lookup in substring.

```cpp
int System::String::IndexOf(char_t c, int startIndex, int count) const
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | Znak do wyszukania. |
| startIndex | int | [Index](../../index/) do rozpoczęcia wyszukiwania. |
| count | int | Liczba znaków do przeszukania. |

### Wartość zwracana

[Index](../../index/) pierwszej pozycji znaku od startIndex lub -1, jeśli nie znaleziono.

## String::IndexOf(const String\&, int) const metoda


Substring forward lookup.

```cpp
int System::String::IndexOf(const String &str, int startIndex=0) const
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Podciąg do wyszukania. |
| startIndex | int | Pozycja w ciągu źródłowym, od której rozpocząć wyszukiwanie. |

### Wartość zwracana

[Index](../../index/) pierwszego znalezionego podciągu lub -1, jeśli nie znaleziono. Dla pustego ciągu wyszukiwania zawsze zwraca startIndex.

## String::IndexOf(const String\&, int, System::StringComparison) const metoda


Substring forward lookup.

```cpp
int System::String::IndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Podciąg do wyszukania. |
| startIndex | int | Pozycja w ciągu źródłowym, od której rozpocząć wyszukiwanie. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) tryb. |

### Wartość zwracana

[Index](../../index/) pierwszego znalezionego podciągu lub -1, jeśli nie znaleziono. Dla pustego ciągu wyszukiwania zawsze zwraca startIndex.

## String::IndexOf(const String\&, int, int, System::StringComparison) const metoda


Substring forward lookup.

```cpp
int System::String::IndexOf(const String &value, int startIndex, int count, System::StringComparison comparisonType) const
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Podciąg do wyszukania. |
| startIndex | int | Pozycja w ciągu źródłowym, od której rozpocząć wyszukiwanie. |
| count | int | liczba znaków do przeszukania. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) tryb. |

### Wartość zwracana

[Index](../../index/) pierwszego znalezionego podciągu lub -1, jeśli nie znaleziono. Dla pustego ciągu wyszukiwania zawsze zwraca startIndex.

## String::IndexOf(const String\&, int, int) const metoda


Substring forward lookup.

```cpp
int System::String::IndexOf(const String &str, int startIndex, int count) const
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Podciąg do wyszukania. |
| startIndex | int | Pozycja w ciągu źródłowym, od której rozpocząć wyszukiwanie. |
| count | int | liczba znaków do przeszukania. |

### Wartość zwracana

[Index](../../index/) pierwszego znalezionego podciągu lub -1, jeśli nie znaleziono. Dla pustego ciągu wyszukiwania zawsze zwraca startIndex.

## Zobacz także

* Enum [StringComparison](../../stringcomparison/)
* Klasa [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)