---
title: Read()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest het opgegeven aantal bytes van de stream en schrijft ze naar de opgegeven byte-array.
type: docs
weight: 391
url: /nl/system.net.security/sslstream/read/
---
## SslStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) methode


Leest het opgegeven aantal bytes van de stream en schrijft ze naar de opgegeven byte-array.

```cpp
int32_t System::Net::Security::SslStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De byte-array om de gelezen bytes naar te schrijven |
| offset | **int32_t** | Een 0-gebaseerde positie in **buffer** om te beginnen met schrijven |
| count | **int32_t** | Het aantal te lezen bytes |

### Retourwaarde

Het aantal gelezen bytes

## SslStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) methode


Leest het opgegeven aantal bytes van de stream en schrijft ze naar de opgegeven byte-array.

```cpp
int32_t System::Net::Security::SslStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | De byte-array om de gelezen bytes naar te schrijven |
| offset | **int32_t** | Een 0-gebaseerde positie in **buffer** om te beginnen met schrijven |
| count | **int32_t** | Het aantal te lezen bytes |

### Retourwaarde

Het aantal gelezen bytes

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)