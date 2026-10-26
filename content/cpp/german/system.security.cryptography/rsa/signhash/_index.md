---
title: SignHash()
second_title: Aspose.Slides für C++ API-Referenz
description: Berechnet die Signatur für den angegebenen Hashwert.
type: docs
weight: 144
url: /de/system.security.cryptography/rsa/signhash/
---
## RSA::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) Methode

Berechnet die Signatur für den angegebenen Hashwert.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hashwert. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Hash-Algorithmus. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Padding-Modus. liefert [RSA](../) Signatur für den angegebenen Hash. |

## Siehe auch

* Typdefinition [ByteArrayPtr](../../../system/bytearrayptr/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [RSASignaturePadding](../../rsasignaturepadding/)
* Klasse [RSA](../)
* Struktur [HashAlgorithmName](../../hashalgorithmname/)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)