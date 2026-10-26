---
title: VerifySignature()
second_title: Aspose.Slides pro C++ API Reference
description: Ověří DSA podpis pro určená data.
type: docs
weight: 118
url: /cs/system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature(ByteArrayPtr, ByteArrayPtr) metoda


Ověřuje podpis [DSA](../../dsa/) pro určená data.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) signed with **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../../dsa/) signature. |

### Návratová hodnota

true - pokud **rgb_signature** odpovídá podpisu [DSA](../../dsa/) vypočítanému nad **rgb_hash**, jinak - false.

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Třída [DSACryptoServiceProvider](../)
* Jmenný prostor [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)