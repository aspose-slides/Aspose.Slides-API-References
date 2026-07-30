---
title: Write()
second_title: Aspose.Slides pro C++ – reference API
description: Zapisuje určený podrozsah bajtů ze zadaného pole bajtů do proudu.
type: docs
weight: 53
url: /cs/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda


Zapisuje určený podrozsah bajtů ze zadaného pole bajtů do proudu.

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole obsahující bajty k zápisu |
| offset | **int32_t** | Index (0-základní) prvku v **buffer**, kde podrozsah zápisu začíná |
| count | **int32_t** | Počet prvků v podrozsahu k zápisu |

## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda


Zapisuje určený podrozsah bajtů ze zadaného pole bajtů do proudu.

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Pohled na pole obsahující bajty k zápisu |
| offset | **int32_t** | Index (0-základní) prvku v **buffer**, kde podrozsah zápisu začíná |
| count | **int32_t** | Počet prvků v podrozsahu k zápisu |

## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) metoda


Zapisuje určený podrozsah bajtů ze zadaného pole bajtů do proudu.

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| N | Velikost zásobníkového pole |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | Zásobníkové pole obsahující bajty k zápisu |
| offset | **int32_t** | Index (0-základní) prvku v **buffer**, kde podrozsah zápisu začíná |
| count | **int32_t** | Počet prvků v podrozsahu k zápisu |

## Stream::Write(const System::ReadOnlySpan\<uint8_t\>\&) metoda


Zapisuje určený podrozsah bajtů ze zadaného rozsahu bajtů do proudu.

```cpp
virtual void System::IO::Stream::Write(const System::ReadOnlySpan<uint8_t> &buffer)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [System::ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | Rozsah bajtů, ze kterého se čtou zapisované bajty |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [Stream](../)
* Třída [ReadOnlySpan](../../../system/readonlyspan/)
* Jmenný prostor [System::IO](../../)
* Library [Aspose.Slides](../../../)