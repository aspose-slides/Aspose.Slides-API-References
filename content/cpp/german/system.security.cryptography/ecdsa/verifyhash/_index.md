---
title: VerifyHash()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft die Datensignatur.
type: docs
weight: 118
url: /de/system.security.cryptography/ecdsa/verifyhash/
---
## ECDsa::VerifyHash(ByteArrayPtr, ByteArrayPtr) Methode


Überprüft die Datensignatur.

```cpp
virtual bool System::Security::Cryptography::ECDsa::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hash, der für die empfangenen Daten berechnet wurde. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Signatur wie empfangen. |

### Rückgabewert

True, wenn die Signatur gültig ist, sonst false.

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klasse [ECDsa](../)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)