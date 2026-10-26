---
title: SignHash()
second_title: Aspose.Slides voor C++ API-referentie
description: Berekent de handtekening voor de opgegeven hashwaarde.
type: docs
weight: 196
url: /nl/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) methode


Berekent de handtekening voor de opgegeven hashwaarde.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hashwaarde. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Hash-algoritme. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Padding-modus. retourneer [RSA](../../rsa/) handtekening voor de opgegeven hash. |

## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) methode


Berekent de handtekening van de opgegeven invoerwaarde. Niet geïmplementeerd.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hashwaarde van de te ondertekenen gegevens. |
| str | const [String](../../../system/string/)\& | Hash-algoritme-identificator die is gebruikt om de hash te maken. |

### Returnwaarde

[RSA](../../rsa/) handtekening voor opgegeven gegevens.

## Zie ook

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSACryptoServiceProvider](../)
* Class [String](../../../system/string/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)