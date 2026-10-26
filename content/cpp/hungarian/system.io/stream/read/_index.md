---
title: Read()
second_title: Aspose.Slides for C++ API referencia
description: A megadott számú bájtot olvassa be a folyamatról, és a megadott bájt tömbbe írja.
type: docs
weight: 27
url: /hu/system.io/stream/read/
---
## Stream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


A megadott számú bájtot olvassa be a folyamatról, és a megadott bájt tömbbe írja.

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A bájt tömb, ahová a beolvasott bájtokat írja |
| offset | **int32_t** | 0-bázisú pozíció a **buffer**-ben, ahol a írás kezdődik |
| count | **int32_t** | A beolvasandó bájtok száma |

### Visszatérési érték

A beolvasott bájtok száma

## Stream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


A megadott számú bájtot olvassa be a folyamatról, és a megadott bájt tömbbe írja.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | A bájt tömb nézet, ahová a beolvasott bájtokat írja |
| offset | **int32_t** | 0-bázisú pozíció a **buffer**-ben, ahol a írás kezdődik |
| count | **int32_t** | A beolvasandó bájtok száma |

### Visszatérési érték

A beolvasott bájtok száma

## Stream::Read(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) method


A megadott számú bájtot olvassa be a folyamatról, és a megadott bájt tömbbe írja.

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| N | A verem tömb mérete |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | A bájt veremtömb, ahová a beolvasott bájtokat írja |
| offset | **int32_t** | 0-bázisú pozíció a **buffer**-ben, ahol a írás kezdődik |
| count | **int32_t** | A beolvasandó bájtok száma |

### Visszatérési érték

A beolvasott bájtok száma

## Stream::Read(const System::Span\<uint8_t\>\&) method


A megadott számú bájtot olvassa be a folyamatról, és a megadott bájt tartományba írja.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Span<uint8_t> &buffer)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [System::Span](../../../system/span/)\<**uint8_t**\>\& | A bájt tartomány, ahová a beolvasott bájtokat írja |

### Visszatérési érték

A beolvasott bájtok száma

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [Stream](../)
* Osztály [Span](../../../system/span/)
* Névtere [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)