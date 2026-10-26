---
title: Write()
second_title: Aspose.Slides voor C++ API Referentie
description: Schrijft het opgegeven deelbereik van bytes uit de opgegeven byte-array naar de stream.
type: docs
weight: 92
url: /nl/system.io/memorystream/write/
---
## MemoryStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) methode


Schrijft het opgegeven deelbereik van bytes uit de opgegeven byte-array naar de stream.

```cpp
void System::IO::MemoryStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De array die de te schrijven bytes bevat |
| offset | **int32_t** | Een 0-gebaseerde index van het element in **buffer** waarop het te schrijven deelbereik begint |
| count | **int32_t** | Het aantal elementen in het te schrijven deelbereik |

## MemoryStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) methode


Schrijft het opgegeven deelbereik van bytes uit de opgegeven byte-array naar de stream.

```cpp
void System::IO::MemoryStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | De array-view die de te schrijven bytes bevat |
| offset | **int32_t** | Een 0-gebaseerde index van het element in **buffer** waarop het te schrijven deelbereik begint |
| count | **int32_t** | Het aantal elementen in het te schrijven deelbereik |

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [MemoryStream](../)
* Naamruimte [System::IO](../../)
* Library [Aspose.Slides](../../../)