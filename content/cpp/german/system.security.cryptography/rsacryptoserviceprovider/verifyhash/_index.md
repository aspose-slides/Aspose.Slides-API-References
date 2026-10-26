---
title: VerifyHash()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft die Datensignatur.
type: docs
weight: 222
url: /de/system.security.cryptography/rsacryptoserviceprovider/verifyhash/
---
## RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) Methode

Überprüft die Datensignatur.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hash, der für empfangene Daten berechnet wurde. |
| str | const [String](../../../system/string/)\& | Name des verwendeten Hash-Algorithmus. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Empfangene Signatur. |

### Rückgabewert

True, wenn die Signatur gültig ist, sonst false.

## RSACryptoServiceProvider::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) Methode

Überprüft, ob die Signatur des angegebenen Hashwerts gültig ist.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hashwert der signierten Daten. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Signaturdaten. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Padding-Modus. Gibt true zurück, wenn die Signatur gültig ist, andernfalls false. |

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [RSACryptoServiceProvider](../)
* Klasse [RSASignaturePadding](../../rsasignaturepadding/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namensraum [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)