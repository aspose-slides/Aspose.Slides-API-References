---
title: VerifyData()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft die Datensignatur.
type: docs
weight: 209
url: /de/system.security.cryptography/dsacryptoserviceprovider/verifydata/
---
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) Methode


Überprüft die Datensignatur.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const ByteArrayPtr &signature)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) zum Überprüfen der Signatur. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signatur wie empfangen. |

### Rückgabewert

Wahr, wenn die Signatur gültig ist, ansonsten falsch.

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) Methode


Überprüft, ob die Signatur der angegebenen Daten gültig ist.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signierte Daten. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signaturdaten. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. Rückgabewert: wahr, wenn die Signatur gültig ist, sonst falsch. |

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) Methode


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
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. Rückgabewert: wahr, wenn die Signatur gültig ist, sonst falsch. |

## DSACryptoServiceProvider::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) Methode


Überprüft, ob die Signatur des angegebenen Binärstroms gültig ist.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Signierte Daten. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signaturdaten. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. Rückgabewert: wahr, wenn die Signatur gültig ist, sonst falsch. |

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Klasse [DSACryptoServiceProvider](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namensraum [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)