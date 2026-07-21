---
title: VerifyData()
second_title: Aspose.Slides для C++ — справочник API
description: Проверяет, является ли подпись указанных данных действительной.
type: docs
weight: 105
url: /ru/system.security.cryptography/ecdsa/verifydata/
---
## ECDsa::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method

Проверяет, является ли подпись указанных данных действительной.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Подписанные данные. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Данные подписи. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Алгоритм хеширования. возвращает true, если подпись действительна, иначе — false. |

## ECDsa::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) method

Проверяет, является ли подпись указанных данных действительной.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Подписанные данные. |
| offset | **int32_t** | Смещение в **data**. |
| count | **int32_t** | Количество байтов для хеширования. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Данные подписи. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Алгоритм хеширования. возвращает true, если подпись действительна, иначе — false. |

## ECDsa::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method

Проверяет, является ли подпись указанного двоичного потока действительной.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Подписанные данные. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Данные подписи. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Алгоритм хеширования. возвращает true, если подпись действительна, иначе — false. |

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Класс [ECDsa](../)
* Структура [HashAlgorithmName](../../hashalgorithmname/)
* Пространство имён [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)