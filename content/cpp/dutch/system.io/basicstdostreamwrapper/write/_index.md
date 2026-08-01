---
title: Write()
second_title: Aspose.Slides voor C++ API-referentie
description: Als de wrappermodus binair is, schrijft deze de opgegeven subreeks bytes uit de opgegeven byte-array naar de stroom; anders wordt de opgegeven subreeks bytes uit de opgegeven byte-array naar het type char_type geconverteerd en vervolgens het resultaat naar de stroom geschreven.
type: docs
weight: 79
url: /nl/system.io/basicstdostreamwrapper/write/
---
## BasicSTDOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) methode


Als de wrappermodus binair is, schrijft deze de opgegeven subreeks bytes uit de opgegeven byte-array naar de stroom; anders wordt de opgegeven subreeks bytes uit de opgegeven byte-array naar het type char_type geconverteerd en vervolgens het resultaat naar de stroom geschreven.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De array die de te schrijven bytes bevat |
| offset | **int32_t** | Een index beginnend bij 0 van het element in **buffer** waarop het te schrijven subbereik begint |
| count | **int32_t** | Het aantal elementen in het subbereik dat geschreven moet worden |

## BasicSTDOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) methode


Schrijft de opgegeven subreeks bytes uit de opgegeven byte-array naar de stroom.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | De array-view die de te schrijven bytes bevat |
| offset | **int32_t** | Een index beginnend bij 0 van het element in **buffer** waarop het te schrijven subbereik begint |
| count | **int32_t** | Het aantal elementen in het subbereik dat geschreven moet worden |

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [BasicSTDOStreamWrapper](../)
* Naamruimte [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)