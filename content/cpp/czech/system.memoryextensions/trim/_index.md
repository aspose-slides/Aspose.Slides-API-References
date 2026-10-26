---
title: Trim()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Odstraňuje zadaný prvek z obou konců typovaného rozsahu.
type: docs
weight: 365
url: /cs/system.memoryextensions/trim/
---
## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, T) function

Odstraňuje zadaný prvek z obou konců typovaného rozsahu.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, T trimElement)
```

### Parametry šablony

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rozsah, který se má oříznout |
| trimElement | T | Prvek, který se má oříznout |

### Návratová hodnota

Nový rozsah se zadaným prvkem oříznutým z obou konců

## System::MemoryExtensions::Trim(Span\<T\>\&, T) function

Odstraňuje zadaný prvek z obou konců měnitelného typovaného rozsahu.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, T trimElement)
```

### Parametry šablony

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Měnitelné rozsah, který se má oříznout |
| trimElement | T | Prvek, který se má oříznout |

### Návratová hodnota

Nový rozsah se zadaným prvkem oříznutým z obou konců

## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Odstraňuje zadané prvky z obou konců typovaného rozsahu.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Parametry šablony

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rozsah, který se má oříznout |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Prvky, které se mají oříznout |

### Návratová hodnota

Nový rozsah se zadanými prvky oříznutými z obou konců

## System::MemoryExtensions::Trim(Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Odstraňuje zadané prvky z obou konců měnitelného typovaného rozsahu.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Parametry šablony

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Měnitelné rozsah, který se má oříznout |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Prvky, které se mají oříznout |

### Návratová hodnota

Nový rozsah se zadanými prvky oříznutými z obou konců

## System::MemoryExtensions::Trim(const ReadOnlySpan\<char16_t\>\&) function

Odstraňuje bílé znaky z obou konců znakového rozsahu.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::Trim(const ReadOnlySpan<char16_t> &span)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Znakový rozsah, který se má oříznout |

### Návratová hodnota

Nový rozsah s oříznutými bílými znaky z obou konců

## System::MemoryExtensions::Trim(Span\<char16_t\>\&) function

Odstraňuje bílé znaky z obou konců měnitelného znakového rozsahu.

```cpp
Span<char16_t> System::MemoryExtensions::Trim(Span<char16_t> &span)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Měnitelný znakový rozsah, který se má oříznout |

### Návratová hodnota

Nový rozsah s oříznutými bílými znaky z obou konců

## Viz také

* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Třída [Span](../../system/span/)
* Obor názvů [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)