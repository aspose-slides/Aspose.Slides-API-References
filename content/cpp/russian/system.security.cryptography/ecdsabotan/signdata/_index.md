---
title: SignData()
second_title: Справочник API Aspose.Slides для C++
description: Вычисляет хеш-значение указанного массива данных и подписывает результат.
type: docs
weight: 131
url: /ru/system.security.cryptography/ecdsabotan/signdata/
---
## ECDsaBotan::SignData(const ByteArrayPtr\&) метод


Вычисляет хеш-значение указанного массива данных и подписывает результат.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Массив входных данных. возврат подписи ECDSA для входных данных. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t) метод


Вычисляет хеш-значение указанного массива данных и подписывает результат.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Массив входных данных. |
| offset | **int32_t** | Смещение в **data**. |
| count | **int32_t** | Количество байтов, используемых как входные данные. возврат подписи ECDSA для входных данных. |

## ECDsaBotan::SignData(const StreamPtr\&) метод


Вычисляет хеш-значение указанного бинарного потока и подписывает результат.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const StreamPtr &stream)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Бинарный поток. возврат подписи ECDSA для входных данных. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) метод


Вычисляет хеш-значение указанного массива данных с использованием указанного алгоритма хеширования и подписывает результат.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Массив входных данных. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Алгоритм хеширования. возврат подписи ECDSA для входных данных. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) метод


Вычисляет хеш-значение указанного массива данных с использованием указанного алгоритма хеширования и подписывает результат.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Массив входных данных. |
| offset | **int32_t** | Смещение в **data**. |
| count | **int32_t** | Количество байтов, используемых как входные данные. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Алгоритм хеширования. возврат подписи ECDSA для входных данных. |

## ECDsaBotan::SignData(const StreamPtr\&, const HashAlgorithmName\&) метод


Вычисляет хеш-значение указанного бинарного потока с использованием указанного алгоритма хеширования и подписывает результат.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Бинарный поток. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Алгоритм хеширования. возврат подписи ECDSA для входных данных. |

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)