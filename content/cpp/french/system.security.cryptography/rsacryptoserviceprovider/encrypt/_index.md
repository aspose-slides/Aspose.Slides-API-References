---
title: Encrypt()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crypte le message. Non implémenté.
type: docs
weight: 118
url: /fr/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr\&, bool) méthode


Crypte le message. Non implémenté.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) à chiffrer. |
| use_oaep | **bool** | True pour utiliser le remplissage OAEP, false pour utiliser le remplissage PKCS#1 v1.5. |

### Valeur de retour

Tableau de données chiffrées.

## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) méthode


Crypte les données d'entrée en utilisant le mode de remplissage spécifié.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) tableau à chiffrer. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Mode de remplissage. |

### Valeur de retour

Données chiffrées au format de tableau d'octets.

## Voir aussi

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [RSACryptoServiceProvider](../)
* Classe [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Espace de noms [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)