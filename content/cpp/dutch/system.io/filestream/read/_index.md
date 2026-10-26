---
title: Read()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest het opgegeven aantal bytes van de stream en schrijft ze naar de opgegeven byte-array.
type: docs
weight: 183
url: /nl/system.io/filestream/read/
---
## FileStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Leest het opgegeven aantal bytes van de stream en schrijft ze naar de opgegeven byte-array.

```cpp
int32_t System::IO::FileStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De byte-array waarin de gelezen bytes worden geschreven. |
| offset | **int32_t** | Een 0-gebaseerde positie in **buffer** om te beginnen met schrijven. |
| count | **int32_t** | Het aantal bytes om te lezen. |

### Retourwaarde

Het aantal gelezen bytes.

## FileStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Leest het opgegeven aantal bytes van de stream en schrijft ze naar de opgegeven byte-array.

```cpp
int32_t System::IO::FileStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | De byte-array view waarin de gelezen bytes worden geschreven. |
| offset | **int32_t** | Een 0-gebaseerde positie in **buffer** om te beginnen met schrijven. |
| count | **int32_t** | Het aantal bytes om te lezen. |

### Retourwaarde

Het aantal gelezen bytes.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)