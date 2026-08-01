---
title: Read()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest het opgegeven aantal bytes uit de stream en schrijft ze naar de opgegeven byte array.
type: docs
weight: 79
url: /nl/system.io/memorystream/read/
---
## MemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) methode


Leest het opgegeven aantal bytes uit de stream en schrijft ze naar de opgegeven byte-array.

```cpp
int32_t System::IO::MemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De byte-array waarin de gelezen bytes moeten worden geschreven |
| offset | **int32_t** | Een op 0 gebaseerde positie in **buffer** om te beginnen met schrijven |
| count | **int32_t** | Het aantal te lezen bytes |

### Retourwaarde

Het aantal gelezen bytes

## MemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) methode


Leest het opgegeven aantal bytes uit de stream en schrijft ze naar de opgegeven byte-array.

```cpp
int32_t System::IO::MemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | De byte-array-view waarin de gelezen bytes moeten worden geschreven |
| offset | **int32_t** | Een op 0 gebaseerde positie in **buffer** om te beginnen met schrijven |
| count | **int32_t** | Het aantal te lezen bytes |

### Retourwaarde

Het aantal gelezen bytes

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [MemoryStream](../)
* Naamruimte [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)