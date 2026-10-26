---
title: VerifySignature()
second_title: Aspose.Slides für C++ API Referenz
description: Überprüft die DSA-Signatur für die angegebenen Daten.
type: docs
weight: 118
url: /de/system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature(ByteArrayPtr, ByteArrayPtr) Methode

Verifiziert die [DSA](../../dsa/) Signatur für die angegebenen Daten.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) signiert mit **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../../dsa/) Signatur. |

### Rückgabewert

true - wenn **rgb_signature** mit der [DSA](../../dsa/) Signatur übereinstimmt, die aus **rgb_hash** berechnet wurde, sonst - false.

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klasse [DSACryptoServiceProvider](../)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)