---
title: VerifySignature()
second_title: Aspose.Slides för C++ API-referens
description: Verifiera DSA-signatur för den angivna datan.
type: docs
weight: 118
url: /sv/system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature(ByteArrayPtr, ByteArrayPtr) metod

Verifiera [DSA](../../dsa/) signatur för den angivna datan.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) signerad med **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../../dsa/) signatur. |

### Returvärde

true - om **rgb_signature** matchar den [DSA](../../dsa/) signaturen som beräknas på **rgb_hash**, annars - false.

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)