---
title: Decrypt()
second_title: Référence de l'API Aspose.Slides pour C++
description: Déchiffre le message. Non implémenté.
type: docs
weight: 105
url: /fr/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) méthode


Déchiffre le message. Non implémenté.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) à déchiffrer. |
| use_oaep | **bool** | True to use OAEP padding, false to use PKCS#1 v1.5 padding. |

### Valeur de retour

Tableau de données déchiffrées.

## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) méthode


Déchiffre les données d'entrée en utilisant le mode de remplissage spécifié.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) tableau à déchiffrer. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Mode de remplissage. |

### Valeur de retour

Données déchiffrées au format tableau d'octets.

## Voir aussi

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSACryptoServiceProvider](../)
* Class [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)