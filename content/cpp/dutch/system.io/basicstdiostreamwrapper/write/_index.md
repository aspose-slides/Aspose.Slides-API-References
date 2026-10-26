---
title: Write()
second_title: Aspose.Slides voor C++ API-referentie
description: Als de wikkelmodus binair is, schrijft het de opgegeven deelreeks bytes van de opgegeven byte-array naar de stream; anders wordt de opgegeven deelreeks bytes van de opgegeven byte-array geconverteerd naar het type char_type en vervolgens wordt het resultaat naar de stream geschreven.
type: docs
weight: 79
url: /nl/system.io/basicstdiostreamwrapper/write/
---
## BasicSTDIOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) methode

Als de wikkelmodus binair is, schrijft het de opgegeven deelreeks bytes van de opgegeven byte-array naar de stream; anders wordt de opgegeven deelreeks bytes van de opgegeven byte-array naar het type char_type geconverteerd en vervolgens wordt het resultaat naar de stream geschreven.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De array die de te schrijven bytes bevat |
| offset | **int32_t** | Een index beginnend bij 0 van het element in **buffer** waarop de deelreeks die moet worden geschreven begint |
| count | **int32_t** | Het aantal elementen in de te schrijven deelreeks |

## BasicSTDIOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) methode

Schrijft de opgegeven deelreeks bytes van de opgegeven byte-array naar de stream.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | De array-view die de te schrijven bytes bevat |
| offset | **int32_t** | Een index beginnend bij 0 van het element in **buffer** waarop de deelreeks die moet worden geschreven begint |
| count | **int32_t** | Het aantal elementen in de te schrijven deelreeks |

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [BasicSTDIOStreamWrapper](../)
* Naamruimte [System::IO](../../)
* Library [Aspose.Slides](../../../)