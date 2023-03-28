---
title: ComputeHash()
second_title: Aspose.Slides for C++ API Reference
description: Hashes buffer.
type: docs
weight: 14
url: /cpp/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\&) method


Hashes buffer.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Source buffer. |

### Return Value

Calculated hash value.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)
## HashAlgorithm::ComputeHash(const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\&, int, int) method


Hashes buffer slice.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Source buffer. |
| offset | int | Offset in the source buffer. |
| count | int | Number of bytes to use from the source buffer. |

### Return Value

Calculated hash value.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)
## HashAlgorithm::ComputeHash([SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> const\&) method


Reads stream until end and calculates hash for the data read.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> const\& | Stream to read data from. |

### Return Value

Calculated hash value for the whole stream data.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)
