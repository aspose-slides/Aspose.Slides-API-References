---
title: TrimEnd()
second_title: Aspose.Slides pro C++ API Reference
description: Odstraní zadaný prvek z konce typovaného rozsahu.
type: docs
weight: 378
url: /cs/system.memoryextensions/trimend/
---
## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const T\&) funkce

Odstraní zadaný prvek z konce typovaného rozsahu.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const T &trimElement)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků v rozsahu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rozsah k oříznutí |
| trimElement | const T\& | Prvek k oříznutí |

### Návratová hodnota

Nový rozsah, ze kterého byl odebrán specifikovaný prvek na konci

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const T\&) funkce

Odstraní specifikovaný prvek z konce modifikovatelného typovaného rozsahu.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const T &trimElement)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků v rozsahu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Modifikovatelný rozsah k oříznutí |
| trimElement | const T\& | Prvek k oříznutí |

### Návratová hodnota

Nový rozsah, ze kterého byl odebrán specifikovaný prvek na konci

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkce

Odstraní zadané prvky z konce typovaného rozsahu.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků v rozsahu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rozsah k oříznutí |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Prvky k oříznutí |

### Návratová hodnota

Nový rozsah, ze kterého byly odebrány specifikované prvky na konci

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkce

Odstraní zadané prvky z konce modifikovatelného typovaného rozsahu.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků v rozsahu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Modifikovatelný rozsah k oříznutí |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Prvky k oříznutí |

### Návratová hodnota

Nový rozsah, ze kterého byly odebrány specifikované prvky na konci

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&) funkce

Odstraní znaky bílých mezer z konce znakového rozsahu.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Znakový rozsah k oříznutí |

### Návratová hodnota

Nový rozsah s odebranými bílými mezerami z konce

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&) funkce

Odstraní znaky bílých mezer z konce modifikovatelného znakového rozsahu.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Modifikovatelný znakový rozsah k oříznutí |

### Návratová hodnota

Nový rozsah s odebranými bílými mezerami z konce

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, char16_t) funkce

Odstraní zadaný znak z konce znakového rozsahu.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Znakový rozsah k oříznutí |
| trimchar | char16_t | Znak k oříznutí |

### Návratová hodnota

Nový rozsah s odebraným specifikovaným znakem z konce

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, char16_t) funkce

Odstraní zadaný znak z konce modifikovatelného znakového rozsahu.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, char16_t trimchar)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Modifikovatelný znakový rozsah k oříznutí |
| trimchar | char16_t | Znak k oříznutí |

### Návratová hodnota

Nový rozsah s odebraným specifikovaným znakem z konce

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) funkce

Odstraní zadané znaky z konce znakového rozsahu.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimChars)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Znakový rozsah k oříznutí |
| trimChars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Znaky k oříznutí |

### Návratová hodnota

Nový rozsah, ze kterého byly odebrány specifikované znaky na konci

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) funkce

Odstraní zadané znaky z konce modifikovatelného znakového rozsahu.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Modifikovatelný znakový rozsah k oříznutí |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Znaky k oříznutí |

### Návratová hodnota

Nový rozsah, ze kterého byly odebrány specifikované znaky na konci

## Viz také

* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Třída [Span](../../system/span/)
* Jmenný prostor [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)