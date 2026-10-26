---
title: VerifySignature()
second_title: Aspose.Slides für C++ API Referenz
description: Verifiziert die DSA-Signatur für die angegebenen Daten.
type: docs
weight: 14
url: /de/system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature(ByteArrayPtr, ByteArrayPtr) Methode

Verifiziert die [DSA](../) Signatur für die angegebenen Daten.

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) signiert mit **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../) Signatur. |

### Rückgabewert

true - falls **rgb_signature** mit der [DSA](../) Signatur übereinstimmt, die aus **rgb_hash** berechnet wurde, andernfalls - false.

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klasse [DSA](../)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)