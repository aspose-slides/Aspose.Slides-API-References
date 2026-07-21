---
title: VerifyData()
second_title: Aspose.Slides для C++ справочник API
description: Проверяет, что подпись указанных данных действительна.
type: docs
weight: 170
url: /ru/system.security.cryptography/ecdsabotan/verifydata/
---
## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) метод

Проверяет, что подпись указанных данных действительна.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Подписанные данные. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Данные подписи. возвращает true, если подпись действительна, иначе - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&) метод

Проверяет, что подпись указанных данных действительна.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Подписанные данные. |
| offset | **int32_t** | Смещение в **data**. |
| count | **int32_t** | Количество байтов для хеширования. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Данные подписи. возвращает true, если подпись действительна, иначе - false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&) метод

Проверяет, что подпись указанного двоичного потока действительна.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Подписанные данные. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Данные подписи. возвращает true, если подпись действительна, иначе - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) метод

Проверяет, что подпись указанных данных действительна.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Подписанные данные. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Данные подписи. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Алгоритм хеширования. возвращает true, если подпись действительна, иначе - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) метод

Проверяет, что подпись указанных данных действительна.

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
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Алгоритм хеширования. возвращает true, если подпись действительна, иначе - false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) метод

Проверяет, что подпись указанного двоичного потока действительна.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Подписанные данные. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Данные подписи. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Алгоритм хеширования. возвращает true, если подпись действительна, иначе - false. |

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Класс [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Пространство имён [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)