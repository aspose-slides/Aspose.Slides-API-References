---
title: VerifyData()
second_title: Aspose.Slides voor C++ API-referentie
description: Verifieert of de handtekening van de opgegeven gegevens geldig is.
type: docs
weight: 157
url: /nl/system.security.cryptography/rsa/verifydata/
---
## RSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) methode

Verifieert of de handtekening van de opgegeven gegevens geldig is.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ondertekende gegevens. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Handtekeninggegevens. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritme. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Padding-modus. return true if signature is valid, otherwise - false. |

## RSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) methode

Verifieert of de handtekening van de opgegeven gegevens geldig is.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ondertekende gegevens. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Aantal bytes om te hashen. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Handtekeninggegevens. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritme. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Padding-modus. return true if signature is valid, otherwise - false. |

## RSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) methode

Verifieert of de handtekening van de opgegeven binaire stream geldig is.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Ondertekende gegevens. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Handtekeninggegevens. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritme. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Padding-modus. return true if signature is valid, otherwise - false. |

## Zie ook

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)