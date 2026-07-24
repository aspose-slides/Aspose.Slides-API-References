---
title: VerifyData()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft, ob die Signatur der angegebenen Daten gültig ist.
type: docs
weight: 157
url: /de/system.security.cryptography/rsa/verifydata/
---
## RSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) Methode

Überprüft, ob die Signatur der angegebenen Daten gültig ist.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signierte Daten. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signaturdaten. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Padding-Modus. Gibt true zurück, wenn die Signatur gültig ist, sonst - false. |

## RSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) Methode

Überprüft, ob die Signatur der angegebenen Daten gültig ist.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signierte Daten. |
| offset | **int32_t** | Versatz in **data**. |
| count | **int32_t** | Anzahl der zu hashenden Bytes. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signaturdaten. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Padding-Modus. Gibt true zurück, wenn die Signatur gültig ist, sonst - false. |

## RSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) Methode

Überprüft, ob die Signatur des angegebenen Binärstreams gültig ist.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Signierte Daten. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signaturdaten. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Padding-Modus. Gibt true zurück, wenn die Signatur gültig ist, sonst - false. |

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Klasse [RSASignaturePadding](../../rsasignaturepadding/)
* Klasse [RSA](../)
* Struktur [HashAlgorithmName](../../hashalgorithmname/)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)