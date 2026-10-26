---
title: StartsWith()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar om span börjar med det angivna värdet.
type: docs
weight: 352
url: /sv/system.memoryextensions/startswith/
---
## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const T\&) funktion


Kontrollerar om span börjar med det angivna value.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const T &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i span |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span som ska kontrolleras |
| value | const T\& | Value att kontrollera i början av span |

### Returvärde

true om span börjar med value, false annars

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funktion


Kontrollerar om span börjar med det angivna value span.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spans |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span som ska kontrolleras |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span som innehåller values att kontrollera i början |

### Returvärde

true om span börjar med value span, false annars

## System::MemoryExtensions::StartsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funktion


Kontrollerar om den modifierbara span börjar med det angivna endast läsning value span.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spans |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Den modifierbara span som ska kontrolleras |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Den endast läsning span som innehåller values att kontrollera |

### Returvärde

true om den modifierbara span börjar med value span, false annars

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) funktion


Kontrollerar om den endast läsning span börjar med det angivna modifierbara value span.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spans |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Den endast läsning span som ska kontrolleras |
| value | const [Span](../../system/span/)\<T\>\& | Den modifierbara span som innehåller values att kontrollera |

### Returvärde

true om den endast läsning span börjar med value span, false annars

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) funktion


Kontrollerar om tecken span börjar med det angivna value span med strängjämförelse.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Tecken span att kontrollera |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Tecken span som innehåller values att kontrollera |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Typen av strängjämförelse att utföra |

### Returvärde

true om span börjar med value span, false annars

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<String\>\&, const char16_t *) funktion


Kontrollerar om en String span börjar med den angivna teckenarrayen.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<String> &span, const char16_t *val)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<[String](../../system/string/)\>\& | String span att kontrollera |
| val | const char16_t * | Teckenarrayen att kontrollera i början |

### Returvärde

true om span börjar med teckenarrayen, false annars

## Se även

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Class [String](../../system/string/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)