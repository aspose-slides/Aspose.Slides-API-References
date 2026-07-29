---
title: Encrypt()
second_title: Aspose.Slides för C++ API-referens
description: Krypterar meddelandet. Ej implementerad.
type: docs
weight: 118
url: /sv/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr\&, bool) metod


Krypterar meddelandet. Ej implementerad.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) att kryptera. |
| use_oaep | **bool** | Sant för att använda OAEP-padding, falskt för att använda PKCS#1 v1.5-padding. |

### Returvärde

Krypterad dataarray.

## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) metod


Krypterar indata med det angivna paddningsläget.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) array att kryptera. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Paddingläge. |

### Returvärde

Krypterad data i bytearrayformat.

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [RSACryptoServiceProvider](../)
* Klass [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)