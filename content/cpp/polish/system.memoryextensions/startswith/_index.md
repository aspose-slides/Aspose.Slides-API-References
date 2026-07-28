---
title: StartsWith()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Sprawdza, czy zakres zaczyna się od określonej wartości.
type: docs
weight: 352
url: /pl/system.memoryextensions/startswith/
---
## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const T\&) funkcja

Sprawdza, czy zakres zaczyna się od określonej wartości.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const T &value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres do sprawdzenia |
| value | const T\& | Wartość do sprawdzenia na początku zakresu |

### Wartość zwracana

true, jeśli zakres zaczyna się od wartości, false w przeciwnym razie

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja

Sprawdza, czy zakres zaczyna się od określonego zakresu wartości.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres do sprawdzenia |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres zawierający wartości do sprawdzenia na początku |

### Wartość zwracana

true, jeśli zakres zaczyna się od zakresu wartości, false w przeciwnym razie

## System::MemoryExtensions::StartsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja

Sprawdza, czy zmienny zakres zaczyna się od określonego tylko do odczytu zakresu wartości.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Zmienny zakres do sprawdzenia |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres tylko do odczytu zawierający wartości do sprawdzenia |

### Wartość zwracana

true, jeśli zakres zaczyna się od zakresu wartości, false w przeciwnym razie

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) funkcja

Sprawdza, czy zakres tylko do odczytu zaczyna się od określonego zmiennego zakresu wartości.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres tylko do odczytu do sprawdzenia |
| value | const [Span](../../system/span/)\<T\>\& | Zmienny zakres zawierający wartości do sprawdzenia |

### Wartość zwracana

true, jeśli zakres zaczyna się od zakresu wartości, false w przeciwnym razie

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) funkcja

Sprawdza, czy zakres znaków zaczyna się od określonego zakresu wartości przy użyciu porównania ciągów.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Zakres znaków do sprawdzenia |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Zakres znaków zawierający wartości do sprawdzenia |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Typ porównania ciągów do wykonania |

### Wartość zwracana

true, jeśli zakres zaczyna się od zakresu wartości, false w przeciwnym razie

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<String\>\&, const char16_t *) funkcja

Sprawdza, czy zakres ciągu znaków zaczyna się od określonej tablicy znaków.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<String> &span, const char16_t *val)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<[String](../../system/string/)\>\& | Zakres ciągu znaków do sprawdzenia |
| val | const char16_t * | Tablica znaków do sprawdzenia na początku |

### Wartość zwracana

true, jeśli zakres zaczyna się od tablicy znaków, false w przeciwnym razie

## Zobacz także

* Enum [StringComparison](../../system/stringcomparison/)
* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Klasa [Span](../../system/span/)
* Klasa [String](../../system/string/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)