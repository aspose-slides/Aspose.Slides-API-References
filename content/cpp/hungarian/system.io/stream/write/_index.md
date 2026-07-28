---
title: Write()
second_title: Aspose.Slides C++ API Referencia
description: A megadott bájt tömbből a megadott bájt alintervallumot írja a streambe.
type: docs
weight: 53
url: /hu/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metódus


A megadott bájt tömbből a megadott bájt alintervallumot írja a streambe.

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A bájtok írásához szükséges tömb |
| offset | **int32_t** | A **buffer** elemének 0-bázisú indexe, ahol a írandó alintervallum kezdődik |
| count | **int32_t** | A írandó alintervallum elemeinek száma |

## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metódus


A megadott bájt tömbből a megadott bájt alintervallumot írja a streambe.

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | A bájtok írásához szükséges tömb nézet |
| offset | **int32_t** | A **buffer** elemének 0-bázisú indexe, ahol a írandó alintervallum kezdődik |
| count | **int32_t** | A írandó alintervallum elemeinek száma |

## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) metódus


A megadott bájt tömbből a megadott bájt alintervallumot írja a streambe.

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| N | A verem tömb mérete |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | A bájtok írásához szükséges verem tömb |
| offset | **int32_t** | A **buffer** elemének 0-bázisú indexe, ahol a írandó alintervallum kezdődik |
| count | **int32_t** | A írandó alintervallum elemeinek száma |

## Stream::Write(const System::ReadOnlySpan\<uint8_t\>\&) metódus


A megadott bájt spanból a megadott bájt alintervallumot írja a streambe.

```cpp
virtual void System::IO::Stream::Write(const System::ReadOnlySpan<uint8_t> &buffer)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [System::ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | A bájt span, amelyből az írt bájtokat olvassa |

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [Stream](../)
* Osztály [ReadOnlySpan](../../../system/readonlyspan/)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)