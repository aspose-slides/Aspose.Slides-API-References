---
title: EndsWith()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om ett ReadOnlySpan<T> avslutas med ett enda värde.
type: docs
weight: 131
url: /sv/system.memoryextensions/endswith/
---
## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const T\&) function

Avgör om ett ReadOnlySpan<T> avslutas med ett enda värde.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const T &value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | spannet att kontrollera |
| value | const T\& | värdet att kontrollera i slutet av spannen |

### Returvärde

true om spannen avslutas med värdet, false annars

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Avgör om ett ReadOnlySpan<T> avslutas med ett annat ReadOnlySpan<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | spannet att kontrollera |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | spannet att kontrollera i slutet av målsspannet |

### Returvärde

true om spannen avslutas med värdespannet, false annars

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Avgör om ett Span<T> avslutas med ett ReadOnlySpan<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | spannet att kontrollera |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | spannet att kontrollera i slutet av målsspannet |

### Returvärde

true om spannen avslutas med värdespannet, false annars

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) function

Avgör om ett ReadOnlySpan<T> avslutas med ett Span<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | spannet att kontrollera |
| value | const [Span](../../system/span/)\<T\>\& | spannet att kontrollera i slutet av målsspannet |

### Returvärde

true om spannen avslutas med värdespannet, false annars

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const Span\<T\>\&) function

Avgör om ett Span<T> avslutas med ett annat Span<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const Span<T> &value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | spannet att kontrollera |
| value | const [Span](../../system/span/)\<T\>\& | spannet att kontrollera i slutet av målsspannet |

### Returvärde

true om spannen avslutas med värdespannet, false annars

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function

Avgör om ett ReadOnlySpan<char16_t> avslutas med det angivna värdet med hjälp av StringComparison.

```cpp
bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | spannet att kontrollera |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | värdet att kontrollera i slutet av spannen |
| comparisonType | [StringComparison](../../system/stringcomparison/) | strängjämförelsetyp att använda |

### Returvärde

true om spannen avslutas med värdet, false annars

## Se även

* Enum [StringComparison](../../system/stringcomparison/)
* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions](../)
* Bibliotek [Aspose.Slides](../../)