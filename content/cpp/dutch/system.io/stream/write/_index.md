---
title: Write()
second_title: Aspose.Slides voor C++ API-referentie
description: Schrijft het opgegeven subbereik van bytes van de opgegeven byte-array naar de stream.
type: docs
weight: 53
url: /nl/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) methode

Schrijft het opgegeven subbereik van bytes van de opgegeven byte-array naar de stream.

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De array met de bytes die moeten worden geschreven |
| offset | **int32_t** | Een index vanaf 0 van het element in **buffer** waar het subbereik om te schrijven begint |
| count | **int32_t** | Het aantal elementen in het subbereik dat moet worden geschreven |

## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) methode

Schrijft het opgegeven subbereik van bytes van de opgegeven byte-array naar de stream.

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | De arrayview met de bytes die moeten worden geschreven |
| offset | **int32_t** | Een index vanaf 0 van het element in **buffer** waar het subbereik om te schrijven begint |
| count | **int32_t** | Het aantal elementen in het subbereik dat moet worden geschreven |

## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) methode

Schrijft het opgegeven subbereik van bytes van de opgegeven byte-array naar de stream.

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| N | De grootte van de stackarray |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | De stackarray met de bytes die moeten worden geschreven |
| offset | **int32_t** | Een index vanaf 0 van het element in **buffer** waar het subbereik om te schrijven begint |
| count | **int32_t** | Het aantal elementen in het subbereik dat moet worden geschreven |

## Stream::Write(const System::ReadOnlySpan\<uint8_t\>\&) methode

Schrijft het opgegeven subbereik van bytes van de opgegeven byte-span naar de stream.

```cpp
virtual void System::IO::Stream::Write(const System::ReadOnlySpan<uint8_t> &buffer)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [System::ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | De byte-span waarvan de te schrijven bytes worden gelezen |

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Stream](../)
* Klasse [ReadOnlySpan](../../../system/readonlyspan/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)