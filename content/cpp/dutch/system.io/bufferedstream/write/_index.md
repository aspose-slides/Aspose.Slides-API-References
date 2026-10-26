---
title: Write()
second_title: Aspose.Slides voor C++ API-referentie
description: Schrijft het opgegeven subbereik van bytes uit de opgegeven byte-array naar de onderliggende stream.
type: docs
weight: 66
url: /nl/system.io/bufferedstream/write/
---
## BufferedStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) methode

Schrijft het opgegeven subbereik van bytes uit de opgegeven byte-array naar de onderliggende stream.

```cpp
virtual void System::IO::BufferedStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De array die de bytes bevat die moeten worden geschreven |
| offset | **int32_t** | Een nulgebaseerde index van het ellemnet in **buffer** waarop het subbereik dat moet worden geschreven begint |
| count | **int32_t** | Het aantal elementen in het subbereik dat moet worden geschreven |

## BufferedStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) methode

Schrijft het opgegeven subbereik van bytes uit de opgegeven byte-array naar de onderliggende stream.

```cpp
virtual void System::IO::BufferedStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | De array die de bytes bevat die moeten worden geschreven |
| offset | **int32_t** | Een nulgebaseerde index van het ellemnet in **buffer** waarop het subbereik dat moet worden geschreven begint |
| count | **int32_t** | Het aantal elementen in het subbereik dat moet worden geschreven |

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [BufferedStream](../)
* Naamruimte [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)