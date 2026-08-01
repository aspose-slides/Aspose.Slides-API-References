---
title: Read()
second_title: Aspose.Slides voor C++ API-referentie
description: Als de verpakkingsmodus binair is, leest het het opgegeven aantal bytes van de stream, anders leest het het opgegeven aantal tekens en converteert deze naar het type uint8_t. Schrijft het resultaat van het lezen naar de opgegeven byte-array.
type: docs
weight: 66
url: /nl/system.io/basicstdistreamwrapper/read/
---
## BasicSTDIStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) methode


Als de verpakkingsmodus binair is, leest het het opgegeven aantal bytes van de stream, anders leest het het opgegeven aantal tekens en converteert ze naar het type **uint8_t**. Schrijft het resultaat van het lezen naar de opgegeven byte-array.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De byte-array waarin de gelezen bytes worden geschreven |
| offset | **int32_t** | Een 0-gebaseerde positie in **buffer** waar het schrijven begint |
| count | **int32_t** | Het aantal bytes dat moet worden gelezen |

### Retourwaarde

Aantal bytes of tekens gelezen

## BasicSTDIStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) methode


Leest het opgegeven aantal bytes van de stream en schrijft ze naar de opgegeven byte-array.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | De byte-array-view waarin de gelezen bytes worden geschreven |
| offset | **int32_t** | Een 0-gebaseerde positie in **buffer** waar het schrijven begint |
| count | **int32_t** | Het aantal bytes dat moet worden gelezen |

### Retourwaarde

Het aantal bytes gelezen

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [BasicSTDIStreamWrapper](../)
* Naamruimte [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)