---
title: Read()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest het opgegeven aantal bytes van de stream en schrijft ze naar de opgegeven byte-array.
type: docs
weight: 27
url: /nl/system.io/stream/read/
---
## Stream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Leest het opgegeven aantal bytes van de stream en schrijft ze naar de opgegeven byte-array.

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De byte-array waarin de gelezen bytes worden geschreven |
| offset | **int32_t** | Een positie gebaseerd op 0 in **buffer** waar het schrijven begint |
| count | **int32_t** | Het aantal bytes dat gelezen moet worden |

### Retourwaarde

Het aantal gelezen bytes

## Stream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Leest het opgegeven aantal bytes van de stream en schrijft ze naar de opgegeven byte-array.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | De byte-array-view waarin de gelezen bytes worden geschreven |
| offset | **int32_t** | Een positie gebaseerd op 0 in **buffer** waar het schrijven begint |
| count | **int32_t** | Het aantal bytes dat gelezen moet worden |

### Retourwaarde

Het aantal gelezen bytes

## Stream::Read(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) method


Leest het opgegeven aantal bytes van de stream en schrijft ze naar de opgegeven byte-array.

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| N | De grootte van de stack-array |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | De byte-stack-array waarin de gelezen bytes worden geschreven |
| offset | **int32_t** | Een positie gebaseerd op 0 in **buffer** waar het schrijven begint |
| count | **int32_t** | Het aantal bytes dat gelezen moet worden |

### Retourwaarde

Het aantal gelezen bytes

## Stream::Read(const System::Span\<uint8_t\>\&) method


Leest het opgegeven aantal bytes van de stream en schrijft ze naar de opgegeven byte-span.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Span<uint8_t> &buffer)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [System::Span](../../../system/span/)\<**uint8_t**\>\& | De byte-span waarin de gelezen bytes worden geschreven |

### Retourwaarde

Het aantal gelezen bytes

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Stream](../)
* Klasse [Span](../../../system/span/)
* Naamruimte [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)