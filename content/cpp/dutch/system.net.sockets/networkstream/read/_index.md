---
title: Read()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest het opgegeven aantal bytes uit de stroom en schrijft ze naar de opgegeven byte-array.
type: docs
weight: 196
url: /nl/system.net.sockets/networkstream/read/
---
## NetworkStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) methode


Leest het opgegeven aantal bytes uit de stroom en schrijft ze naar de opgegeven byte-array.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De byte-array waarin de gelezen bytes zullen worden geschreven. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| size | **int32_t** | Het aantal bytes om te lezen. |

### Retourwaarde

Het aantal gelezen bytes.

## NetworkStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) methode


Leest het opgegeven aantal bytes uit de stroom en schrijft ze naar de opgegeven byte-array.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | De byte-array-view om de gelezen bytes naartoe te schrijven |
| offset | **int32_t** | Een op 0 gebaseerde positie in **buffer** om te beginnen met schrijven |
| size | **int32_t** | Het aantal bytes om te lezen |

### Retourwaarde

Het aantal gelezen bytes

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [NetworkStream](../)
* Naamruimte [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)