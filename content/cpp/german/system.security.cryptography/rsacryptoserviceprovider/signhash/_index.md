---
title: SignHash()
second_title: Aspose.Slides für C++ API-Referenz
description: Berechnet die Signatur für den angegebenen Hash-Wert.
type: docs
weight: 196
url: /de/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) Methode

Berechnet die Signatur für den angegebenen Hash-Wert.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```



### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hash-Wert. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Hash-Algorithmus. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Auffüllmodus. gibt die [RSA](../../rsa/) Signatur für den angegebenen Hash zurück. |

## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) Methode

Berechnet die Signatur des angegebenen Eingabewerts. Nicht implementiert.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hash-Wert der zu signierenden Daten. |
| str | const [String](../../../system/string/)\& | Hash-Algorithmus-Identifikator, der zum Erzeugen des Hashs verwendet wurde. |

### Rückgabewert

[RSA](../../rsa/) Signatur für die angegebenen Daten.

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [RSASignaturePadding](../../rsasignaturepadding/)
* Klasse [RSACryptoServiceProvider](../)
* Klasse [String](../../../system/string/)
* Struktur [HashAlgorithmName](../../hashalgorithmname/)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)