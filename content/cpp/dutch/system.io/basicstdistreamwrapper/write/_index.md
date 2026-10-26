---
title: Write()
second_title: Aspose.Slides voor C++ API-referentie
description: Als de wrap-modus binair is, schrijft het de opgegeven subreeks van bytes uit de opgegeven byte-array naar de stream, anders wordt de opgegeven subreeks van bytes uit de opgegeven byte-array naar het type char_type geconverteerd en vervolgens wordt het resultaat naar de stream geschreven. Niet ondersteund!
type: docs
weight: 79
url: /nl/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Als de wrap-modus binair is, schrijft het de opgegeven subreeks van bytes uit de opgegeven byte-array naar de stream; anders wordt de opgegeven subreeks van bytes uit de opgegeven byte-array naar het type char_type geconverteerd en vervolgens wordt het resultaat naar de stream geschreven. Niet ondersteund!

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De array die de te schrijven bytes bevat. |
| offset | **int32_t** | Een op 0 beginnende index van het element in **buffer** waar de subreeks om te schrijven begint. |
| count | **int32_t** | Het aantal elementen in de subreeks die moet worden geschreven. |

## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Schrijft de opgegeven subreeks van bytes uit de opgegeven byte-array naar de stream.

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | De array-view die de te schrijven bytes bevat |
| offset | **int32_t** | Een op 0 beginnende index van het element in **buffer** waar de subreeks om te schrijven begint |
| count | **int32_t** | Het aantal elementen in de subreeks die moet worden geschreven |

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [BasicSTDIStreamWrapper](../)
* Naamruimte [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)