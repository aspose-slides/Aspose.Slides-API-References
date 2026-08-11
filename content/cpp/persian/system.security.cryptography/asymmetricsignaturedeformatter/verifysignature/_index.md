---
title: VerifySignature()
second_title: مرجع API Aspose.Slides برای C++
description: امضای داده‌ها را تأیید می‌کند.
type: docs
weight: 27
url: /fa/system.security.cryptography/asymmetricsignaturedeformatter/verifysignature/
---
## AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method

امضای داده‌ها را تأیید می‌کند.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) امضا شده با **rgbSignature**. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | امضایی که باید برای داده‌ها تأیید شود. |

### مقدار بازگشت

True if signature check succeeds, false otherwise.

## AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr\<HashAlgorithm\>, System::ArrayPtr\<uint8_t\>) method

امضای داده‌ها را تأیید می‌کند. Not implemented.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr<HashAlgorithm> hash, System::ArrayPtr<uint8_t> rgbSignature)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | الگوریتم مورد استفاده برای هش‌سازی. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | امضایی که باید برای داده‌ها تأیید شود. |

### مقدار بازگشت

True if signature check succeeds, false otherwise.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [AsymmetricSignatureDeformatter](../)
* Class [HashAlgorithm](../../hashalgorithm/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)