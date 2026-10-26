---
title: SignHash()
second_title: Aspose.Slides für C++ API-Referenz
description: Berechnet die Signatur des angegebenen Eingabewerts.
type: docs
weight: 196
url: /de/system.security.cryptography/dsacryptoserviceprovider/signhash/
---
## DSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) Methode

Berechnet die Signatur des angegebenen Eingabewerts.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hashwert der zu signierenden Daten. |
| str | const [String](../../../system/string/)\& | Kennung des Hash-Algorithmus, der zum Erstellen des Hashs verwendet wurde. |

### Rückgabewert

[DSA](../../dsa/) Signatur für die angegebenen Daten.

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [DSACryptoServiceProvider](../)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)