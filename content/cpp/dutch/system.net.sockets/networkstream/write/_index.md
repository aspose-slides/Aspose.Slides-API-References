---
title: Write()
second_title: Aspose.Slides voor C++ API-referentie
description: Schrijft het opgegeven deelbereik van bytes van de opgegeven byte-array naar de stream.
type: docs
weight: 209
url: /nl/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) methode


Schrijft het opgegeven deelbereik van bytes van de opgegeven byte-array naar de stream.

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De array die de te schrijven bytes bevat. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| size | **int32_t** | Het aantal elementen in het deelbereik dat moet worden geschreven. |

## NetworkStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) methode


Schrijft het opgegeven deelbereik van bytes van de opgegeven byte-array naar de stream.

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | De arrayview die de te schrijven bytes bevat |
| offset | **int32_t** | Een op 0 gebaseerde index van het element in **buffer** waarop het te schrijven deelbereik begint |
| size | **int32_t** | Het aantal elementen in het deelbereik dat moet worden geschreven |

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [NetworkStream](../)
* Naamruimte [System::Net::Sockets](../../)
* Bibliotheek [Aspose.Slides](../../../)