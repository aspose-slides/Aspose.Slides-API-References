---
title: Read()
second_title: Aspose.Slides voor C++ API-referentie
description: Als de wrap-modus binair is, leest het het opgegeven aantal bytes van de stream, anders leest het het opgegeven aantal tekens en zet deze om naar type uint8_t. Schrijft het resultaat van het lezen naar de opgegeven byte-array. Niet ondersteund!
type: docs
weight: 66
url: /nl/system.io/basicstdostreamwrapper/read/
---
## BasicSTDOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) methode


Als de wrap-modus binair is, leest het het opgegeven aantal bytes van de stroom, anders leest het het opgegeven aantal tekens en zet ze om naar type **uint8_t**. Schrijft het resultaat van het lezen naar de opgegeven byte-array. Niet ondersteund!

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De byte-array om de gelezen bytes in te schrijven |
| offset | **int32_t** | Een 0-gebaseerde positie in **buffer** om te beginnen met schrijven |
| count | **int32_t** | Het aantal bytes om te lezen |

### Retourwaarde

Aantal bytes of tekens gelezen

## BasicSTDOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) methode


Leest het opgegeven aantal bytes van de stroom en schrijft ze naar de opgegeven byte-array.

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | De byte-array-view om de gelezen bytes in te schrijven |
| offset | **int32_t** | Een 0-gebaseerde positie in **buffer** om te beginnen met schrijven |
| count | **int32_t** | Het aantal bytes om te lezen |

### Retourwaarde

Het aantal bytes gelezen

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [BasicSTDOStreamWrapper](../)
* Naamruimte [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)