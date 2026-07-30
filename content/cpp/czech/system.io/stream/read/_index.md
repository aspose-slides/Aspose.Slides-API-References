---
title: Read()
second_title: Aspose.Slides pro C++ - reference API
description: Načte z proudu zadaný počet bajtů a zapíše je do určeného pole bajtů.
type: docs
weight: 27
url: /cs/system.io/stream/read/
---
## Stream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda


Načte z proudu zadaný počet bajtů a zapíše je do určeného pole bajtů.

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole bajtů, do kterého se zapíší přečtené bajty |
| offset | **int32_t** | Pozice v **buffer** počítaná od nuly, kde začít zápis |
| count | **int32_t** | Počet bajtů k načtení |

### Návratová hodnota

Počet načtených bajtů

## Stream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda


Načte z proudu zadaný počet bajtů a zapíše je do určeného pole bajtů.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Pohled na pole bajtů, do kterého se zapíší přečtené bajty |
| offset | **int32_t** | Pozice v **buffer** počítaná od nuly, kde začít zápis |
| count | **int32_t** | Počet bajtů k načtení |

### Návratová hodnota

Počet načtených bajtů

## Stream::Read(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) metoda


Načte z proudu zadaný počet bajtů a zapíše je do určeného pole bajtů.

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| N | Velikost zásobníkového pole |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | Pole zásobníkových bajtů, do kterého se zapíší přečtené bajty |
| offset | **int32_t** | Pozice v **buffer** počítaná od nuly, kde začít zápis |
| count | **int32_t** | Počet bajtů k načtení |

### Návratová hodnota

Počet načtených bajtů

## Stream::Read(const System::Span\<uint8_t\>\&) metoda


Načte z proudu zadaný počet bajtů a zapíše je do určeného rozsahu bajtů.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Span<uint8_t> &buffer)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [System::Span](../../../system/span/)\<**uint8_t**\>\& | Rozsah bajtů, do kterého se zapíší přečtené bajty |

### Návratová hodnota

Počet načtených bajtů

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [Stream](../)
* Třída [Span](../../../system/span/)
* Obor názvů [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)