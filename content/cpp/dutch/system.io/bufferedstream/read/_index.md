---
title: Read()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest het opgegeven aantal bytes van de onderliggende stream en schrijft ze naar de opgegeven byte-array.
type: docs
weight: 53
url: /nl/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Leest het opgegeven aantal bytes van de onderliggende stream en schrijft ze naar de opgegeven byte-array.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De byte-array waarin de gelezen bytes worden geschreven |
| offset | **int32_t** | Een 0-gebaseerde positie in **buffer** om te beginnen met schrijven |
| count | **int32_t** | Het aantal bytes om te lezen |

### Retourwaarde

Het aantal gelezen bytes

## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Leest het opgegeven aantal bytes van de onderliggende stream en schrijft ze naar de opgegeven byte-array.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | De byte-array waarin de gelezen bytes worden geschreven |
| offset | **int32_t** | Een 0-gebaseerde positie in **buffer** om te beginnen met schrijven |
| count | **int32_t** | Het aantal bytes om te lezen |

### Retourwaarde

Het aantal gelezen bytes

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)