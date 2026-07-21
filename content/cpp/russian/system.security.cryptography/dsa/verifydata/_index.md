---
title: VerifyData()
second_title: Справка API Aspose.Slides для C++
description: Проверяет, действительна ли подпись указанных данных.
type: docs
weight: 92
url: /ru/system.security.cryptography/dsa/verifydata/
---
## DSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method

Проверяет, действительна ли подпись указанных данных.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Подписанные данные. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Данные подписи. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Алгоритм хеширования. возвращает true, если подпись действительна, иначе - false. |

## DSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) method

Проверяет, действительна ли подпись указанных данных.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Подписанные данные. |
| offset | **int32_t** | Смещение в **data**. |
| count | **int32_t** | Количество байтов для хеширования. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Данные подписи. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Алгоритм хеширования. возвращает true, если подпись действительна, иначе - false. |

## DSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method

Проверяет, действительна ли подпись указанного бинарного потока.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Подписанные данные. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Данные подписи. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Алгоритм хеширования. возвращает true, если подпись действительна, иначе - false. |

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)