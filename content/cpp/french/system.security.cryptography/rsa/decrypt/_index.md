---
title: Decrypt()
second_title: Référence API Aspose.Slides for C++
description: Déchiffre les données d'entrée en utilisant le mode de remplissage spécifié.
type: docs
weight: 27
url: /fr/system.security.cryptography/rsa/decrypt/
---
## RSA::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) méthode


Déchiffre les données d'entrée en utilisant le mode de remplissage spécifié.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) tableau à déchiffrer. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Mode de remplissage. |

### Valeur de retour

Données déchiffrées au format tableau d'octets.

## Voir aussi

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Classe [RSA](../)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)