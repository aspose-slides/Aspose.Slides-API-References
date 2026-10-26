---
title: Write()
second_title: Aspose.Slides voor C++ API-referentie
description: Schrijft het opgegeven subbereik van bytes uit de opgegeven byte-array naar de stream.
type: docs
weight: 248
url: /nl/system.io/filestream/write/
---
## FileStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) methode

Schrijft het opgegeven subbereik van bytes uit de opgegeven byte-array naar de stream.

```cpp
void System::IO::FileStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De array die de te schrijven bytes bevat. |
| offset | **int32_t** | Een 0-gebaseerde index van het element in **buffer** waarop het te schrijven subbereik begint. |
| count | **int32_t** | Het aantal elementen in het subbereik dat moet worden geschreven. |

## FileStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) methode

Schrijft het opgegeven subbereik van bytes uit de opgegeven byte-array naar de stream.

```cpp
void System::IO::FileStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | De array-view die de te schrijven bytes bevat. |
| offset | **int32_t** | Een 0-gebaseerde index van het element in **buffer** waarop het te schrijven subbereik begint. |
| count | **int32_t** | Het aantal elementen in het subbereik dat moet worden geschreven. |

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [FileStream](../)
* Naamruimte [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)