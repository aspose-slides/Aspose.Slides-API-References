---
title: VerifyData()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft, ob die Signatur der angegebenen Daten gültig ist.
type: docs
weight: 92
url: /de/system.security.cryptography/dsa/verifydata/
---
## DSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) Methode

Überprüft, ob die Signatur der angegebenen Daten gültig ist.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signierte Daten. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signaturdaten. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. Gibt true zurück, wenn die Signatur gültig ist, andernfalls - false. |

## DSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) Methode

Überprüft, ob die Signatur der angegebenen Daten gültig ist.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signierte Daten. |
| offset | **int32_t** | Versatz in **data**. |
| count | **int32_t** | Anzahl der zu hashenden Bytes. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signaturdaten. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. Gibt true zurück, wenn die Signatur gültig ist, andernfalls - false. |

## DSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) Methode

Überprüft, ob die Signatur des angegebenen Binärstreams gültig ist.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Signierte Daten. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signaturdaten. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. Gibt true zurück, wenn die Signatur gültig ist, andernfalls - false. |

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)