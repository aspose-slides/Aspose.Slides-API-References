---
title: Decrypt()
second_title: Aspose.Slides voor C++ API-referentie
description: Ontsleutelt bericht. Niet geïmplementeerd.
type: docs
weight: 105
url: /nl/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) method

Ontsleutelt bericht. Niet geïmplementeerd.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) to decrypt. |
| use_oaep | **bool** | True to use OAEP padding, false to use PKCS#1 v1.5 padding. |

### Retourwaarde

Ontsleutelde gegevensarray.

## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method

Ontsleutelt invoergegevens met de opgegeven opvulmodus.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) array to decrypt. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Opvulmodus. |

### Retourwaarde

Ontsleutelde gegevens in byte-arrayformaat.

## Zie ook

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [RSACryptoServiceProvider](../)
* Klasse [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Naamruimte [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)