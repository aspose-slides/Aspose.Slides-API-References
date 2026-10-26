---
title: VerifyHash()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft die Datensignatur.
type: docs
weight: 222
url: /de/system.security.cryptography/dsacryptoserviceprovider/verifyhash/
---
## DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) Methode

Überprüft die Datensignatur.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hash, der für die empfangenen Daten berechnet wurde. |
| str | const [String](../../../system/string/)\& | Name des verwendeten Hash-Algorithmus. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Empfangene Signatur. |

### Rückgabewert

True, wenn die Signatur gültig ist, false andernfalls.

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [DSACryptoServiceProvider](../)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)