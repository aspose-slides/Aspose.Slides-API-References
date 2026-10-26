---
title: Trim()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Usuwa określony element z obu końców typowanego zakresu.
type: docs
weight: 365
url: /pl/system.memoryextensions/trim/
---
## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, T) funkcja

Usuwa określony element z obu końców zakresu typowanego.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, T trimElement)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres do przycięcia |
| trimElement | T | Element do przycięcia |

### Wartość zwracana

Nowy zakres z określonym elementem usuniętym z obu końców

## System::MemoryExtensions::Trim(Span\<T\>\&, T) funkcja

Usuwa określony element z obu końców modyfikowalnego typowanego zakresu.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, T trimElement)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Modyfikowalny zakres do przycięcia |
| trimElement | T | Element do przycięcia |

### Wartość zwracana

Nowy zakres z określonym elementem usuniętym z obu końców

## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja

Usuwa określone elementy z obu końców zakresu typowanego.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres do przycięcia |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Elementy do przycięcia |

### Wartość zwracana

Nowy zakres z określonymi elementami usuniętymi z obu końców

## System::MemoryExtensions::Trim(Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja

Usuwa określone elementy z obu końców modyfikowalnego typowanego zakresu.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Modyfikowalny zakres do przycięcia |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Elementy do przycięcia |

### Wartość zwracana

Nowy zakres z określonymi elementami usuniętymi z obu końców

## System::MemoryExtensions::Trim(const ReadOnlySpan\<char16_t\>\&) funkcja

Usuwa znaki białe z obu końców zakresu znaków.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::Trim(const ReadOnlySpan<char16_t> &span)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Zakres znaków do przycięcia |

### Wartość zwracana

Nowy zakres z usuniętymi znakami białymi z obu końców

## System::MemoryExtensions::Trim(Span\<char16_t\>\&) funkcja

Usuwa znaki białe z obu końców modyfikowalnego zakresu znaków.

```cpp
Span<char16_t> System::MemoryExtensions::Trim(Span<char16_t> &span)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Modyfikowalny zakres znaków do przycięcia |

### Wartość zwracana

Nowy zakres z usuniętymi znakami białymi z obu końców

## Zobacz także

* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Biblioteka [Aspose.Slides](../../)