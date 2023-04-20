---
title: CreateSignature()
second_title: Aspose.Slides for C++ API Reference
description: Creates the siguature for the specified data.
type: docs
weight: 1
url: /cpp/system.security.cryptography/asymmetricsignatureformatter/createsignature/
---
## AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) method


Creates the siguature for the specified data.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) to calculate hash for. |

### Return Value

Calculated signature in byte array form.

## AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr\<HashAlgorithm\>) method


Creates the signature for the specified hash value.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr<HashAlgorithm> hash)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | Hash algorithm to use when creating signature. |

### Return Value

Calculated signature in byte array form.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [AsymmetricSignatureFormatter](../)
* Class [HashAlgorithm](../../hashalgorithm/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)