---
title: Write()
second_title: Riferimento API di Aspose.Slides per C++
description: Scrive l'intervallo specificato di byte dall'array di byte specificato allo stream.
type: docs
weight: 53
url: /it/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Scrive l'intervallo specificato di byte dall'array di byte specificato allo stream.

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | L'array contenente i byte da scrivere |
| offset | **int32_t** | Un indice base 0 dell'elemento in **buffer** a cui inizia l'intervallo da scrivere |
| count | **int32_t** | Il numero di elementi nell'intervallo da scrivere |

## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Scrive l'intervallo specificato di byte dall'array di byte specificato allo stream.

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista dell'array contenente i byte da scrivere |
| offset | **int32_t** | Un indice base 0 dell'elemento in **buffer** a cui inizia l'intervallo da scrivere |
| count | **int32_t** | Il numero di elementi nell'intervallo da scrivere |

## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) method


Scrive l'intervallo specificato di byte dall'array di byte specificato allo stream.

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```


### Parametri del modello

| Parameter | Description |
| --- | --- |
| N | La dimensione dell'array stack |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | L'array stack contenente i byte da scrivere |
| offset | **int32_t** | Un indice base 0 dell'elemento in **buffer** a cui inizia l'intervallo da scrivere |
| count | **int32_t** | Il numero di elementi nell'intervallo da scrivere |

## Stream::Write(const System::ReadOnlySpan\<uint8_t\>\&) method


Scrive l'intervallo specificato di byte dallo span di byte specificato allo stream.

```cpp
virtual void System::IO::Stream::Write(const System::ReadOnlySpan<uint8_t> &buffer)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [System::ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | Lo span di byte da cui leggere i byte scritti |

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Stream](../)
* Class [ReadOnlySpan](../../../system/readonlyspan/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)