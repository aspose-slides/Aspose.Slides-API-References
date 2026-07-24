---
title: Encrypt()
second_title: Aspose.Slides für C++ API-Referenz
description: Verschlüsselt Eingabedaten mit dem angegebenen Padding-Modus.
type: docs
weight: 53
url: /de/system.security.cryptography/rsa/encrypt/
---
## RSA::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) Methode

Verschlüsselt Eingabedaten mit dem angegebenen Padding-Modus.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) Array zum Verschlüsseln. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Padding-Modus. |

### Rückgabewert

Verschlüsselte Daten im Byte-Array-Format.

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Klasse [RSA](../)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)