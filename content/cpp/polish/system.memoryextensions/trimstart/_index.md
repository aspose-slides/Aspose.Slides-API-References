---
title: TrimStart()
second_title: Aspose.Slides dla C++ API Reference
description: Usuwa określony element z początku typowanego zakresu.
type: docs
weight: 391
url: /pl/system.memoryextensions/trimstart/
---
## System::MemoryExtensions::TrimStart(const ReadOnlySpan<T>&, const T&) funkcja

Usuwa określony element z początku typowanego zakresu.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const T &trimElement)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)<T>& | Zakres do przycięcia |
| trimElement | const T& | Element do przycięcia |

### Wartość zwracana

Nowy zakres z określonym elementem przyciętym od początku

## System::MemoryExtensions::TrimStart(Span<T>&, const T&) funkcja

Usuwa określony element z początku zmiennego typowanego zakresu.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const T &trimElement)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | [Span](../../system/span/)<T>& | Zmienny zakres do przycięcia |
| trimElement | const T& | Element do przycięcia |

### Wartość zwracana

Nowy zakres z określonym elementem przyciętym od początku

## System::MemoryExtensions::TrimStart(const ReadOnlySpan<T>&, const ReadOnlySpan<T>&) funkcja

Usuwa określone elementy z początku typowanego zakresu.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)<T>& | Zakres do przycięcia |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)<T>& | Elementy do przycięcia |

### Wartość zwracana

Nowy zakres z określonymi elementami przyciętymi od początku

## System::MemoryExtensions::TrimStart(Span<T>&, const ReadOnlySpan<T>&) funkcja

Usuwa określone elementy z początku zmiennego typowanego zakresu.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | [Span](../../system/span/)<T>& | Zmienny zakres do przycięcia |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)<T>& | Elementy do przycięcia |

### Wartość zwracana

Nowy zakres z określonymi elementami przyciętymi od początku

## System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t>&) funkcja

Usuwa znaki białych (spacji) z początku zakresu znaków.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)<char16_t>& | Zakres znaków do przycięcia |

### Wartość zwracana

Nowy zakres z białymi znakami przyciętymi od początku

## System::MemoryExtensions::TrimStart(Span<char16_t>&) funkcja

Usuwa znaki białych (spacji) z początku zmiennego zakresu znaków.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | [Span](../../system/span/)<char16_t>& | Zmienny zakres znaków do przycięcia |

### Wartość zwracana

Nowy zakres z białymi znakami przyciętymi od początku

## System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t>&, char16_t) funkcja

Usuwa określony znak z początku zakresu znaków.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)<char16_t>& | Zakres znaków do przycięcia |
| trimchar | char16_t | Znak do przycięcia |

### Wartość zwracana

Nowy zakres z określonym znakiem przyciętym od początku

## System::MemoryExtensions::TrimStart(Span<char16_t>&, char16_t) funkcja

Usuwa określony znak z początku zmiennego zakresu znaków.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, char16_t trimchar)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | [Span](../../system/span/)<char16_t>& | Zmienny zakres znaków do przycięcia |
| trimchar | char16_t | Znak do przycięcia |

### Wartość zwracana

Nowy zakres z określonym znakiem przyciętym od początku

## System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t>&, const ReadOnlySpan<char16_t>&) funkcja

Usuwa określone znaki z początku zakresu znaków.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)<char16_t>& | Zakres znaków do przycięcia |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)<char16_t>& | Znaki do przycięcia |

### Wartość zwracana

Nowy zakres z określonymi znakami przyciętymi od początku

## System::MemoryExtensions::TrimStart(Span<char16_t>&, const ReadOnlySpan<char16_t>&) funkcja

Usuwa określone znaki z początku zmiennego zakresu znaków.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | [Span](../../system/span/)<char16_t>& | Zmienny zakres znaków do przycięcia |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)<char16_t>& | Znaki do przycięcia |

### Wartość zwracana

Nowy zakres z określonymi znakami przyciętymi od początku

## Zobacz także

* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Biblioteka [Aspose.Slides](../../)