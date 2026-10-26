---
title: TrimStart()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort specificerat element från början av ett typat intervall.
type: docs
weight: 391
url: /sv/system.memoryextensions/trimstart/
---
## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const T\&) funktion

Tar bort specificerat element från början av ett typat intervall.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const T &trimElement)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i span |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span som ska trimmas |
| trimElement | const T\& | Elementet som ska trimmas |

### Returvärde

Ett nytt intervall med det specificerade elementet borttaget från början

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const T\&) funktion

Tar bort specificerat element från början av ett muterbart typat intervall.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const T &trimElement)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i span |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Det muterbara span som ska trimmas |
| trimElement | const T\& | Elementet som ska trimmas |

### Returvärde

Ett nytt intervall med det specificerade elementet borttaget från början

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funktion

Tar bort specificerade element från början av ett typat intervall.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i span |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span som ska trimmas |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Elementen som ska trimmas |

### Returvärde

Ett nytt intervall med de specificerade elementen borttagna från början

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const ReadOnlySpan\<T\>\&) funktion

Tar bort specificerade element från början av ett muterbart typat intervall.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i span |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Det muterbara span som ska trimmas |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Elementen som ska trimmas |

### Returvärde

Ett nytt intervall med de specificerade elementen borttagna från början

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&) funktion

Tar bort mellanslagstecken från början av ett teckenintervall.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Teckenintervall som ska trimmas |

### Returvärde

Ett nytt intervall med mellanslagstecken borttagna från början

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&) funktion

Tar bort mellanslagstecken från början av ett muterbart teckenintervall.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Det muterbara teckenintervall som ska trimmas |

### Returvärde

Ett nytt intervall med mellanslagstecken borttagna från början

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, char16_t) funktion

Tar bort specificerat tecken från början av ett teckenintervall.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Teckenintervall som ska trimmas |
| trimchar | char16_t | Tecknet som ska trimmas |

### Returvärde

Ett nytt intervall med det specificerade tecknet borttaget från början

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, char16_t) funktion

Tar bort specificerat tecken från början av ett muterbart teckenintervall.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, char16_t trimchar)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Det muterbara teckenintervall som ska trimmas |
| trimchar | char16_t | Tecknet som ska trimmas |

### Returvärde

Ett nytt intervall med det specificerade tecknet borttaget från början

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) funktion

Tar bort specificerade tecken från början av ett teckenintervall.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Teckenintervall som ska trimmas |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Tecknen som ska trimmas |

### Returvärde

Ett nytt intervall med de specificerade tecknen borttagna från början

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) funktion

Tar bort specificerade tecken från början av ett muterbart teckenintervall.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Det muterbara teckenintervall som ska trimmas |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Tecknen som ska trimmas |

### Returvärde

Ett nytt intervall med de specificerade tecknen borttagna från början

## Se även

* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions](../)
* Bibliotek [Aspose.Slides](../../)