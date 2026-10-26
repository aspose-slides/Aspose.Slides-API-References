---
title: VerifySignature()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Zweryfikuj podpis DSA dla określonych danych.
type: docs
weight: 14
url: /pl/system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature(ByteArrayPtr, ByteArrayPtr) metoda

Zweryfikuj podpis [DSA](../) dla określonych danych.

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) podpisane za pomocą **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../) podpis. |

### Wartość zwracana

true - jeśli **rgb_signature** pasuje do podpisu [DSA](../) obliczonego na **rgb_hash**, w przeciwnym razie - false.

## Zobacz także

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klasa [DSA](../)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)