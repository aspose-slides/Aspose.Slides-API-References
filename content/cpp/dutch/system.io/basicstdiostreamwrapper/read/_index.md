---
title: Read()
second_title: Aspose.Slides voor C++ API-referentie
description: Als de wrappingmodus binair is, leest het het opgegeven aantal bytes uit de stream, anders leest het het opgegeven aantal tekens en converteert deze naar het type uint8_t. Schrijft het resultaat van het lezen naar de opgegeven byte array.
type: docs
weight: 66
url: /nl/system.io/basicstdiostreamwrapper/read/
---
## BasicSTDIOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Als de wrappingmodus binair is, leest het het opgegeven aantal bytes uit de stream, anders leest het het opgegeven aantal tekens en converteert deze naar het type **uint8_t**. Schrijft het resultaat van het lezen naar de opgegeven byte-array.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De byte-array waarin de gelezen bytes worden geschreven |
| offset | **int32_t** | Een 0-gebaseerde positie in **buffer** om te beginnen met schrijven |
| count | **int32_t** | Het aantal bytes om te lezen |

### Retourwaarde

Aantal bytes of tekens gelezen

## BasicSTDIOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Leest het opgegeven aantal bytes uit de stream en schrijft ze naar de opgegeven byte-array.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | De byte-array-view waarin de gelezen bytes worden geschreven |
| offset | **int32_t** | Een 0-gebaseerde positie in **buffer** om te beginnen met schrijven |
| count | **int32_t** | Het aantal bytes om te lezen |

### Retourwaarde

Het aantal gelezen bytes

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [BasicSTDIOStreamWrapper](../)
* Naamruimte [System::IO](../../)
* Library [Aspose.Slides](../../../)