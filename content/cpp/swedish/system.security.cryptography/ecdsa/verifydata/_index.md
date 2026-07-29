---
title: VerifyData()
second_title: Aspose.Slides för C++ API-referens
description: Verifierar att signaturen för de angivna data är giltig.
type: docs
weight: 105
url: /sv/system.security.cryptography/ecdsa/verifydata/
---
## ECDsa::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metod


Verifierar att signaturen för de angivna data är giltig.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signerad data. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signaturdata. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritm. Returnerar true om signaturen är giltig, annars false. |

## ECDsa::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) metod


Verifierar att signaturen för de angivna data är giltig.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signerad data. |
| offset | **int32_t** | Offset i **data**. |
| count | **int32_t** | Antal byte att hash:a. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signaturdata. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritm. Returnerar true om signaturen är giltig, annars false. |

## ECDsa::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metod


Verifierar att signaturen för den angivna binära strömmen är giltig.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Signerad data. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signaturdata. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritm. Returnerar true om signaturen är giltig, annars false. |

## Se också

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Klass [ECDsa](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namnrymd [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)