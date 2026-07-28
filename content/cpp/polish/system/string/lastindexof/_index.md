---
title: LastIndexOf()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Wsteczne wyszukiwanie podciągu.
type: docs
weight: 651
url: /pl/system/string/lastindexof/
---
## String::LastIndexOf(const String\&, int) const metoda

Wsteczne wyszukiwanie podciągu.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const [String](../)\& | Podciąg do wyszukania. |
| startIndex | int | Pozycja w łańcuchu źródłowym, od której rozpocząć wyszukiwanie. |

### Wartość zwracana

[Index](../../index/) ostatniego znalezionego podciągu lub -1, jeśli nie znaleziono. Dla pustego ciągu wyszukiwania zawsze zwraca długość ciągu.

## String::LastIndexOf(const String\&, System::StringComparison) const metoda

Wsteczne wyszukiwanie podciągu.

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const [String](../)\& | Podciąg do wyszukania. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) tryb. |

### Wartość zwracana

[Index](../../index/) ostatniego znalezionego podciągu lub -1, jeśli nie znaleziono. Dla pustego ciągu wyszukiwania zawsze zwraca długość ciągu.

## String::LastIndexOf(const String\&, int, System::StringComparison) const metoda

Wsteczne wyszukiwanie podciągu.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const [String](../)\& | Podciąg do wyszukania. |
| startIndex | int | Pozycja w łańcuchu źródłowym, od której rozpocząć wyszukiwanie. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) tryb. |

### Wartość zwracana

[Index](../../index/) ostatniego znalezionego podciągu lub -1, jeśli nie znaleziono. Dla pustego ciągu wyszukiwania zawsze zwraca długość ciągu.

## String::LastIndexOf(const String\&, int, int, StringComparison) const metoda

Wsteczne wyszukiwanie podciągu.

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../)\& | Podciąg do wyszukania. |
| startIndex | int | Pozycja w łańcuchu źródłowym, od której rozpocząć wyszukiwanie. |
| count | int | Liczba znaków do przeszukania |
| comparisonType | [StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) tryb. |

### Wartość zwracana

[Index](../../index/) ostatniego znalezionego podciągu lub -1, jeśli nie znaleziono. Dla pustego ciągu wyszukiwania zawsze zwraca startIndex+count.

## String::LastIndexOf(char_t) const metoda

Wsteczne wyszukiwanie znaku.

```cpp
int System::String::LastIndexOf(char_t value) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | char_t | Znak do wyszukania. |

### Wartość zwracana

[Index](../../index/) ostatniej pozycji znaku lub -1, jeśli nie znaleziono.

## String::LastIndexOf(char_t, int32_t) const metoda

Wsteczne wyszukiwanie znaku.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | char_t | Znak do wyszukania. |
| startIndex | **int32_t** | [Index](../../index/) do rozpoczęcia wyszukiwania. |

### Wartość zwracana

[Index](../../index/) ostatniej pozycji znaku od startIndex lub -1, jeśli nie znaleziono.

## String::LastIndexOf(char_t, int32_t, int32_t) const metoda

Wsteczne wyszukiwanie znaku.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | char_t | Znak do wyszukania. |
| startIndex | **int32_t** | [Index](../../index/) do rozpoczęcia wyszukiwania. |
| count | **int32_t** | Liczba znaków do przeszukania |

### Wartość zwracana

[Index](../../index/) ostatniej pozycji znaku od startIndex lub -1, jeśli nie znaleziono.

## Zobacz także

* Enum [StringComparison](../../stringcomparison/)
* Klasa [String](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)