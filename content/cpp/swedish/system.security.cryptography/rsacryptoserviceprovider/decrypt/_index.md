---
title: Decrypt()
second_title: Aspose.Slides för C++ API-referens
description: Dekrypterar meddelandet. Inte implementerad.
type: docs
weight: 105
url: /sv/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) metod

Dekrypterar meddelandet. Inte implementerad.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```

### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) att dekryptera. |
| use_oaep | **bool** | True för att använda OAEP-utfyllning, false för att använda PKCS#1 v1.5-utfyllning. |

### Returvärde

Dekrypterad dataarray.

## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) metod

Dekrypterar indata med den angivna utfyllningsläget.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) array att dekryptera. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Utfyllningsläge. |

### Returvärde

Dekrypterad data i bytearrayformat.

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSACryptoServiceProvider](../)
* Class [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)