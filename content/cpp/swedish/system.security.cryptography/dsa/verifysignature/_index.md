---
title: VerifySignature()
second_title: Aspose.Slides för C++ API-referens
description: Verifiera DSA-signatur för den specificerade datan.
type: docs
weight: 14
url: /sv/system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature(ByteArrayPtr, ByteArrayPtr) metod


Verifiera [DSA](../) signatur för den specificerade datan.

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) signerat med **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../) signatur. |

### Returvärde

true - om **rgb_signature** matchar den [DSA](../) signatur som beräknas på **rgb_hash**, annars - false.

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klass [DSA](../)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)