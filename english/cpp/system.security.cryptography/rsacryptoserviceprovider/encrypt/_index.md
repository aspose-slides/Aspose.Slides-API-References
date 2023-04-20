---
title: Encrypt()
second_title: Aspose.Slides for C++ API Reference
description: Encrypts message. Not implemented.
type: docs
weight: 118
url: /cpp/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr\&, bool) method


Encrypts message. Not implemented.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) to encrypt. |
| use_oaep | **bool** | True to use OAEP padding, false to use PKCS#1 v1.5 padding. |

### Return Value

Encrypted data array.

## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method


Encrypts input data using the specified padding mode.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) array to encrypt. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Padding mode. |

### Return Value

Encrypted data in byte array format.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSACryptoServiceProvider](../)
* Class [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)