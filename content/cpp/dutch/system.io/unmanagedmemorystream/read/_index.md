---
title: Read()
second_title: Aspose.Slides voor C++ API Referentie
description: Leest het opgegeven aantal bytes uit de stream en schrijft ze naar de opgegeven byte-array.
type: docs
weight: 144
url: /nl/system.io/unmanagedmemorystream/read/
---
## UnmanagedMemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) methode


Leest het opgegeven aantal bytes uit de stream en schrijft ze naar de opgegeven byte-array.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De byte-array om de gelezen bytes naar toe te schrijven |
| offset | **int32_t** | Een nulgebaseerde positie in **buffer** om te beginnen met schrijven |
| count | **int32_t** | Het aantal bytes om te lezen |

### Retourwaarde

Het aantal gelezen bytes

## UnmanagedMemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) methode


Leest het opgegeven aantal bytes uit de stream en schrijft ze naar de opgegeven byte-array.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | De byte-array-view om de gelezen bytes naar toe te schrijven |
| offset | **int32_t** | Een nulgebaseerde positie in **buffer** om te beginnen met schrijven |
| count | **int32_t** | Het aantal bytes om te lezen |

### Retourwaarde

Het aantal gelezen bytes

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [UnmanagedMemoryStream](../)
* Naamruimte [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)