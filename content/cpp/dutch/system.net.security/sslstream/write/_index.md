---
title: Write()
second_title: Aspose.Slides voor C++ API-referentie
description: Schrijft de opgegeven byte-array naar de stream.
type: docs
weight: 404
url: /nl/system.net.security/sslstream/write/
---
## SslStream::Write(const ArrayPtr\<uint8_t\>\&) methode


Schrijft de opgegeven byte-array naar de stream.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De byte-array die moet worden geschreven. |

## SslStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) methode


Schrijft de opgegeven subreeks van bytes van de opgegeven byte-array naar de stream.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De array die de te schrijven bytes bevat |
| offset | **int32_t** | Een index, beginnend bij 0, van het element in **buffer** waar de subreeks te schrijven begint |
| count | **int32_t** | Het aantal elementen in de subreeks die moet worden geschreven |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&) methode


Schrijft de opgegeven byte-array naar de stream.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | De byte-array die moet worden geschreven. |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) methode


Schrijft de opgegeven subreeks van bytes van de opgegeven byte-array naar de stream.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | De array die de te schrijven bytes bevat |
| offset | **int32_t** | Een index, beginnend bij 0, van het element in **buffer** waar de subreeks te schrijven begint |
| count | **int32_t** | Het aantal elementen in de subreeks die moet worden geschreven |

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)