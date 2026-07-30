---
title: VerifySignature()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Ověří DSA podpis pro zadaná data.
type: docs
weight: 14
url: /cs/system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature(ByteArrayPtr, ByteArrayPtr) metoda

Ověří [DSA](../) podpis pro zadaná data.

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) podepsáno pomocí **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../) podpis. |

### Návratová hodnota

true - pokud **rgb_signature** odpovídá [DSA](../) podpisu vypočtenému na **rgb_hash**, jinak - false.

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Třída [DSA](../)
* Obor názvů [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)