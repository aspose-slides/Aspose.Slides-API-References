---
title: EndsWith()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Określa, czy ReadOnlySpan<T> kończy się pojedynczą wartością.
type: docs
weight: 131
url: /pl/system.memoryextensions/endswith/
---
## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const T\&) funkcja


Określa, czy ReadOnlySpan<T> kończy się pojedynczą wartością.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const T &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres do sprawdzenia |
| value | const T\& | Wartość do sprawdzenia na końcu zakresu |

### Wartość zwracana

true, jeśli zakres kończy się wartością, false w przeciwnym razie

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja


Określa, czy ReadOnlySpan<T> kończy się innym ReadOnlySpan<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres do sprawdzenia |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres do sprawdzenia na końcu docelowego zakresu |

### Wartość zwracana

true, jeśli zakres kończy się zakresem wartości, false w przeciwnym razie

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja


Określa, czy Span<T> kończy się ReadOnlySpan<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Zakres do sprawdzenia |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres do sprawdzenia na końcu docelowego zakresu |

### Wartość zwracana

true, jeśli zakres kończy się zakresem wartości, false w przeciwnym razie

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) funkcja


Określa, czy ReadOnlySpan<T> kończy się Span<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres do sprawdzenia |
| value | const [Span](../../system/span/)\<T\>\& | Zakres do sprawdzenia na końcu docelowego zakresu |

### Wartość zwracana

true, jeśli zakres kończy się zakresem wartości, false w przeciwnym razie

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const Span\<T\>\&) funkcja


Określa, czy Span<T> kończy się innym Span<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const Span<T> &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Zakres do sprawdzenia |
| value | const [Span](../../system/span/)\<T\>\& | Zakres do sprawdzenia na końcu docelowego zakresu |

### Wartość zwracana

true, jeśli zakres kończy się zakresem wartości, false w przeciwnym razie

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) funkcja


Określa, czy ReadOnlySpan<char16_t> kończy się określoną wartością przy użyciu StringComparison.

```cpp
bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Zakres do sprawdzenia |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Wartość do sprawdzenia na końcu zakresu |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Typ porównania łańcucha znaków do użycia |

### Wartość zwracana

true, jeśli zakres kończy się wartością, false w przeciwnym razie

## Zobacz także

* Wyliczenie [StringComparison](../../system/stringcomparison/)
* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Biblioteka [Aspose.Slides](../../)