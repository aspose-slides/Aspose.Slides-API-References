---
title: EndsWith()
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει αν ένα ReadOnlySpan<T> τελειώνει με μια μοναδική τιμή.
type: docs
weight: 131
url: /el/system.memoryextensions/endswith/
---
## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const T\&) function


Καθορίζει αν ένα ReadOnlySpan<T> τελειώνει με μια μοναδική τιμή.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const T &value)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check |
| value | const T\& | The value to check for at the end of the span |

### Τιμή επιστροφής

true if the span ends with the value, false otherwise

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Καθορίζει αν ένα ReadOnlySpan<T> τελειώνει με ένα άλλο ReadOnlySpan<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check for at the end of the target span |

### Τιμή επιστροφής

true if the span ends with the value span, false otherwise

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Καθορίζει αν ένα Span<T> τελειώνει με ένα ReadOnlySpan<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to check |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check for at the end of the target span |

### Τιμή επιστροφής

true if the span ends with the value span, false otherwise

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) function


Καθορίζει αν ένα ReadOnlySpan<T> τελειώνει με ένα Span<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check |
| value | const [Span](../../system/span/)\<T\>\& | The span to check for at the end of the target span |

### Τιμή επιστροφής

true if the span ends with the value span, false otherwise

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const Span\<T\>\&) function


Καθορίζει αν ένα Span<T> τελειώνει με ένα άλλο Span<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const Span<T> &value)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to check |
| value | const [Span](../../system/span/)\<T\>\& | The span to check for at the end of the target span |

### Τιμή επιστροφής

true if the span ends with the value span, false otherwise

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function


Καθορίζει αν ένα ReadOnlySpan<char16_t> τελειώνει με την καθορισμένη τιμή χρησιμοποιώντας StringComparison.

```cpp
bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The span to check |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The value to check for at the end of the span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | The string comparison type to use |

### Τιμή επιστροφής

true if the span ends with the value, false otherwise

## Δείτε επίσης

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)