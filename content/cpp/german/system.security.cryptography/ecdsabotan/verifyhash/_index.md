---
title: VerifyHash()
second_title: Aspose.Slides für C++ API Referenz
description: Überprüft die Datensignatur.
type: docs
weight: 183
url: /de/system.security.cryptography/ecdsabotan/verifyhash/
---
## ECDsaBotan::VerifyHash(ByteArrayPtr, ByteArrayPtr) method

Überprüft die Datensignatur.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hash, der für die empfangenen Daten berechnet wurde. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Signature wie empfangen. |

### Rückgabewert

True, wenn signature gültig ist, sonst false.

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klasse [ECDsaBotan](../)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)