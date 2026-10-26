---
title: Decrypt()
second_title: Aspose.Slides für C++ API Referenz
description: Entschlüsselt Eingabedaten mit dem angegebenen Padding-Modus.
type: docs
weight: 27
url: /de/system.security.cryptography/rsa/decrypt/
---
## RSA::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) Methode


Entschlüsselt Eingabedaten mit dem angegebenen Padding-Modus.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) Array zum Entschlüsseln. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Padding-Modus. |

### Rückgabewert

Entschlüsselte Daten im Byte-Array-Format.

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Klasse [RSA](../)
* Namensraum [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)