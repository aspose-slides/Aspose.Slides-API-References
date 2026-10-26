---
title: AsSpan()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en span från en array.
type: docs
weight: 1
url: /sv/system.memoryextensions/asspan/
---
## System::MemoryExtensions::AsSpan(const ArrayPtr\<T\>\&, int32_t, int32_t) funktion

Skapar en span från en array.

```cpp
template<typename T> Span<T> System::MemoryExtensions::AsSpan(const ArrayPtr<T> &array, int32_t start=0, int32_t length=-1)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på elementen i arrayen. |

### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | Källarrayen. |
| start | **int32_t** | Startindex i arrayen. |
| length | **int32_t** | Spanens längd. |

### Returvärde

Span<T> som omfattar den angivna delen av arrayen.

## System::MemoryExtensions::AsSpan(const String\&, int32_t, int32_t) funktion

Skapar en skrivskyddad span från en sträng.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::AsSpan(const String &text, int32_t start=0, int32_t length=-1)
```

### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| text | const [String](../../system/string/)\& | Källsträngen. |
| start | **int32_t** | Startindex i strängen. |
| length | **int32_t** | Spanens längd. |

### Returvärde

ReadOnlySpan<char16_t> som spänner över den angivna delen av strängen.

## Se även

* Typedef [ArrayPtr](../../system/arrayptr/)
* Klass [Span](../../system/span/)
* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Klass [String](../../system/string/)
* Namnrymd [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)