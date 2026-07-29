---
title: VerifyData()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar datasignatur.
type: docs
weight: 209
url: /sv/system.security.cryptography/dsacryptoserviceprovider/verifydata/
---
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) metod


Kontrollerar datasignatur.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const ByteArrayPtr &signature)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) att kontrollera signatur för. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signaturdata. |

### Returvärde

True if signature is valid, false otherwise.

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metod


Verifierar att signaturen för den angivna datan är giltig.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signerad data. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signaturdata. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritm. return true om signaturen är giltig, annars - false. |

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) metod


Verifierar att signaturen för den angivna datan är giltig.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signerad data. |
| offset | **int32_t** | Förskjutning i **data**. |
| count | **int32_t** | Antal byte att hash:a. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signaturdata. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritm. return true om signaturen är giltig, annars - false. |

## DSACryptoServiceProvider::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metod


Verifierar att signaturen för den angivna binära strömmen är giltig.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Signerad data. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signaturdata. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritm. return true om signaturen är giltig, annars - false. |

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Klass [DSACryptoServiceProvider](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namnrymd [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)