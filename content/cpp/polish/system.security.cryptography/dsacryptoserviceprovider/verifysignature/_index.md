---
title: VerifySignature()
second_title: Aspose.Slides dla C++ - odniesienie do API
description: Weryfikuje podpis DSA dla określonych danych.
type: docs
weight: 118
url: /pl/system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature(ByteArrayPtr, ByteArrayPtr) metoda


Zweryfikuj [DSA](../../dsa/) podpis dla określonych danych.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) podpisany za pomocą **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../../dsa/) podpis. |

### Wartość zwracana

true - jeśli **rgb_signature** pasuje do podpisu [DSA](../../dsa/) obliczonego na **rgb_hash**, w przeciwnym razie - false.

## Zobacz także

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klasa [DSACryptoServiceProvider](../)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)