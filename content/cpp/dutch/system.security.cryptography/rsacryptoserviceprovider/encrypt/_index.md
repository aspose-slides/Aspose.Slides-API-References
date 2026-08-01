---
title: Encrypt()
second_title: Aspose.Slides voor C++ API-referentie
description: Versleutelt bericht. Niet geïmplementeerd.
type: docs
weight: 118
url: /nl/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr\&, bool) methode


Versleutelt bericht. Niet geïmplementeerd.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) om te versleutelen. |
| use_oaep | **bool** | True om OAEP-padding te gebruiken, false om PKCS#1 v1.5-padding te gebruiken. |

### Retourwaarde

Versleutelde gegevensarray.

## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) methode


Versleutelt invoergegevens met de opgegeven padding-modus.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) array om te versleutelen. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Padding-modus. |

### Retourwaarde

Versleutelde gegevens in byte-array-formaat.

## Zie ook

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [RSACryptoServiceProvider](../)
* Klasse [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Namespace [System::Security::Cryptography](../../)
* Bibliotheek [Aspose.Slides](../../../)