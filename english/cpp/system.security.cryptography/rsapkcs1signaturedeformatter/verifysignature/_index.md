---
title: VerifySignature()
second_title: Aspose.Slides for C++ API Reference
description: Verifies the signature of data hash.
type: docs
weight: 40
url: /cpp/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature([System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>) method


Verifies the signature of data hash.

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Hash calculated for the data. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Signature received for data. |

### Return Value

True if signature is valid, false otherwise.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [RSAPKCS1SignatureDeformatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)
