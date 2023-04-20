---
title: VerifySignature()
second_title: Aspose.Slides for C++ API Reference
description: Verifies signature on data.
type: docs
weight: 27
url: /cpp/system.security.cryptography/asymmetricsignaturedeformatter/verifysignature/
---
## AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Verifies signature on data.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) signed with **rgbSignature**. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Signature to be verified for data. |

### Return Value

True if signature check succeeds, false otherwise.

## AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr\<HashAlgorithm\>, System::ArrayPtr\<uint8_t\>) method


Verifies signature on data. Not implemented.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr<HashAlgorithm> hash, System::ArrayPtr<uint8_t> rgbSignature)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | Algorithm to use for hashing. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Signature to be verified for data. |

### Return Value

True if signature check succeeds, false otherwise.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [AsymmetricSignatureDeformatter](../)
* Class [HashAlgorithm](../../hashalgorithm/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)