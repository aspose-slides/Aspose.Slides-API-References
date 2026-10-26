---
title: SequenceEqual()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Określa, czy dwa ReadOnlySpans zawierają identyczne elementy w tej samej kolejności.
type: docs
weight: 326
url: /pl/system.memoryextensions/sequenceequal/
---
## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja

Określa, czy dwa ReadOnlySpans zawierają identyczne elementy w tej samej kolejności.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &first, const ReadOnlySpan<T> &second)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Pierwszy span do porównania |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Drugi span do porównania |

### Wartość zwracana

true jeśli spany mają tę samą długość i wszystkie elementy są równe, false w przeciwnym razie

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja

Określa, czy [Span](../../system/span/) i [ReadOnlySpan](../../system/readonlyspan/) zawierają identyczne elementy w tej samej kolejności.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) do porównania |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) do porównania |

### Wartość zwracana

true jeśli spany mają tę samą długość i wszystkie elementy są równe, false w przeciwnym razie

## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) funkcja

Określa, czy dwa ReadOnlySpans zawierają równe elementy przy użyciu własnego komparatora.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanach |
| TComparer | Typ obiektu komparatora |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Pierwszy span do porównania |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Drugi span do porównania |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Inteligentny wskaźnik do obiektu komparatora używanego przy porównywaniu elementów |

### Wartość zwracana

true jeśli spany mają tę samą długość i komparator uzna wszystkie elementy za równe, false w przeciwnym razie

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) funkcja

Określa, czy [Span](../../system/span/) i [ReadOnlySpan](../../system/readonlyspan/) zawierają równe elementy przy użyciu własnego komparatora.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanach |
| TComparer | Typ obiektu komparatora |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) do porównania |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) do porównania |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Inteligentny wskaźnik do obiektu komparatora używanego przy porównywaniu elementów |

### Wartość zwracana

true jeśli spany mają tę samą długość i komparator uzna wszystkie elementy za równe, false w przeciwnym razie

## Zobacz także

* Definicja typu [SharedPtr](../../system/sharedptr/)
* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Biblioteka [Aspose.Slides](../../)