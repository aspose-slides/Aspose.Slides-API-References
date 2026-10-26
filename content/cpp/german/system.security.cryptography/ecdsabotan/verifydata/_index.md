---
title: VerifyData()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft, ob die Signatur der angegebenen Daten gültig ist.
type: docs
weight: 170
url: /de/system.security.cryptography/ecdsabotan/verifydata/
---
## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) Methode

Überprüft, ob die Signatur der angegebenen Daten gültig ist.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signierte Daten. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signaturdaten. Gibt true zurück, wenn die Signatur gültig ist, andernfalls false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&) Methode

Überprüft, ob die Signatur der angegebenen Daten gültig ist.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signierte Daten. |
| offset | **int32_t** | Versatz in **data**. |
| count | **int32_t** | Anzahl der Bytes, die gehasht werden sollen. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signaturdaten. Gibt true zurück, wenn die Signatur gültig ist, andernfalls false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&) Methode

Überprüft, ob die Signatur des angegebenen Binärstreams gültig ist.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Signierte Daten. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signaturdaten. Gibt true zurück, wenn die Signatur gültig ist, andernfalls false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) Methode

Überprüft, ob die Signatur der angegebenen Daten gültig ist.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signierte Daten. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signaturdaten. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. Gibt true zurück, wenn die Signatur gültig ist, andernfalls false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) Methode

Überprüft, ob die Signatur der angegebenen Daten gültig ist.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signierte Daten. |
| offset | **int32_t** | Versatz in **data**. |
| count | **int32_t** | Anzahl der Bytes, die gehasht werden sollen. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signaturdaten. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. Gibt true zurück, wenn die Signatur gültig ist, andernfalls false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) Methode

Überprüft, ob die Signatur des angegebenen Binärstreams gültig ist.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Signierte Daten. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signaturdaten. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. Gibt true zurück, wenn die Signatur gültig ist, andernfalls false. |

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Klasse [ECDsaBotan](../)
* Struktur [HashAlgorithmName](../../hashalgorithmname/)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)