---
title: Encrypt()
second_title: Référence de l'API Aspose.Slides pour C++
description: Chiffre les données d'entrée à l'aide du mode de remplissage spécifié.
type: docs
weight: 53
url: /fr/system.security.cryptography/rsa/encrypt/
---
## RSA::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) méthode

Chiffre les données d'entrée à l'aide du mode de remplissage spécifié.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) tableau à chiffrer. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Mode de remplissage. |

### Valeur de retour

Données chiffrées au format tableau d'octets.

## Voir aussi

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Classe [RSA](../)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)