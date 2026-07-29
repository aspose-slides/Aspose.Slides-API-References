---
title: Overlaps()
second_title: Aspose.Slides för C++ API-referens
description: Avgör om två ReadOnlySpan överlappar i minnet utan att beräkna förskjutning.
type: docs
weight: 274
url: /sv/system.memoryextensions/overlaps/
---
## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funktion


Avgör om två ReadOnlySpan överlappar i minnet utan att beräkna förskjutning.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Den första spannen att kontrollera för överlappning |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Den andra spannen att kontrollera för överlappning |

### Returvärde

true om spannen delar någon gemensam minnesplats, false annars

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funktion


Avgör om en [Span](../../system/span/) och [ReadOnlySpan](../../system/readonlyspan/) överlappar i minnet utan att beräkna förskjutning.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Den [Span](../../system/span/) som ska kontrolleras för överlappning |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Den [ReadOnlySpan](../../system/readonlyspan/) som ska kontrolleras för överlappning |

### Returvärde

true om spannen delar någon gemensam minnesplats, false annars

## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) funktion


Avgör om två ReadOnlySpan överlappar i minnet och beräknar förskjutningen.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Den första spannen att kontrollera för överlappning |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Den andra spannen att kontrollera för överlappning |
| elementOffset | **int32_t**\& | Utdataparameter som tar emot förskjutningen mellan spannen om de överlappar |

### Returvärde

true om spannen delar någon gemensam minnesplats, false annars

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) funktion


Avgör om en [Span](../../system/span/) och [ReadOnlySpan](../../system/readonlyspan/) överlappar i minnet och beräknar förskjutningen.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Den [Span](../../system/span/) som ska kontrolleras för överlappning |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Den [ReadOnlySpan](../../system/readonlyspan/) som ska kontrolleras för överlappning |
| elementOffset | **int32_t**\& | Utdataparameter som tar emot förskjutningen mellan spannen om de överlappar |

### Returvärde

true om spannen delar någon gemensam minnesplats, false annars

## Se även

* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions](../)
* Bibliotek [Aspose.Slides](../../)