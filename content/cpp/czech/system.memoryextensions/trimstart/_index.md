---
title: TrimStart()
second_title: Aspose.Slides pro C++ – reference API
description: Ořízne zadaný prvek ze začátku typovaného rozsahu.
type: docs
weight: 391
url: /cs/system.memoryextensions/trimstart/
---
## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const T\&) funkce

Ořízne zadaný prvek ze začátku typovaného rozsahu.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const T &trimElement)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků v rozsahu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rozsah, který se má oříznout |
| trimElement | const T\& | Prvek, který se má oříznout |

### Návratová hodnota

Nový rozsah s oříznutým zadaným prvkem ze začátku

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const T\&) funkce

Ořízne zadaný prvek ze začátku měnitelného typovaného rozsahu.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const T &trimElement)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků v rozsahu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Měnitelný rozsah, který se má oříznout |
| trimElement | const T\& | Prvek, který se má oříznout |

### Návratová hodnota

Nový rozsah s oříznutým zadaným prvkem ze začátku

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkce

Ořízne zadané prvky ze začátku typovaného rozsahu.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků v rozsahu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rozsah, který se má oříznout |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Prvky, které se mají oříznout |

### Návratová hodnota

Nový rozsah s oříznutými zadanými prvky ze začátku

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkce

Ořízne zadané prvky ze začátku měnitelného typovaného rozsahu.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků v rozsahu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Měnitelný rozsah, který se má oříznout |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Prvky, které se mají oříznout |

### Návratová hodnota

Nový rozsah s oříznutými zadanými prvky ze začátku

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&) funkce

Ořízne znaky bílých mezer ze začátku znakového rozsahu.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Znakový rozsah, který se má oříznout |

### Návratová hodnota

Nový rozsah s oříznutými bílými mezerami ze začátku

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&) funkce

Ořízne znaky bílých mezer ze začátku měnitelného znakového rozsahu.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Měnitelný znakový rozsah, který se má oříznout |

### Návratová hodnota

Nový rozsah s oříznutými bílými mezerami ze začátku

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, char16_t) funkce

Ořízne zadaný znak ze začátku znakového rozsahu.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Znakový rozsah, který se má oříznout |
| trimchar | char16_t | Znak, který se má oříznout |

### Návratová hodnota

Nový rozsah s oříznutým zadaným znakem ze začátku

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, char16_t) funkce

Ořízne zadaný znak ze začátku měnitelného znakového rozsahu.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, char16_t trimchar)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Měnitelný znakový rozsah, který se má oříznout |
| trimchar | char16_t | Znak, který se má oříznout |

### Návratová hodnota

Nový rozsah s oříznutým zadaným znakem ze začátku

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) funkce

Ořízne zadané znaky ze začátku znakového rozsahu.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Znakový rozsah, který se má oříznout |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Znaky, které se mají oříznout |

### Návratová hodnota

Nový rozsah s oříznutými zadanými znaky ze začátku

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) funkce

Ořízne zadané znaky ze začátku měnitelného znakového rozsahu.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Měnitelný znakový rozsah, který se má oříznout |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Znaky, které se mají oříznout |

### Návratová hodnota

Nový rozsah s oříznutými zadanými znaky ze začátku

## Viz také

* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Třída [Span](../../system/span/)
* Jmenný prostor [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)