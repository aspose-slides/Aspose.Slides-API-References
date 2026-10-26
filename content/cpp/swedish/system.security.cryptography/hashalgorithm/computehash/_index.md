---
title: ComputeHash()
second_title: Aspose.Slides för C++ API-referens
description: Hashar bufferten.
type: docs
weight: 14
url: /sv/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) method

Hashar bufferten.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Källbuffert. |

### Returvärde

Beräknat hashvärde.

## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) method

Hashar ett buffersegment.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Källbuffert. |
| offset | int | Offset i källbufferten. |
| count | int | Antal byte att använda från källbufferten. |

### Returvärde

Beräknat hashvärde.

## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) method

Läser strömmen till slutet och beräknar hash för de lästa data.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> const\& | Ström att läsa data från. |

### Returvärde

Beräknat hashvärde för hela strömdatan.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [HashAlgorithm](../)
* Klass [Stream](../../../system.io/stream/)
* Namnrymd [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)