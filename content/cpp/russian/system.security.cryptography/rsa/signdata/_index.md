---
title: SignData()
second_title: Справочник API Aspose.Slides для C++
description: Вычисляет значение хеша указанного массива данных, используя указанный алгоритм хеширования и заполнение, и подписывает полученный результат.
type: docs
weight: 131
url: /ru/system.security.cryptography/rsa/signdata/
---
## RSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method

Вычисляет значение хеша указанного массива данных, используя указанный алгоритм хеширования и заполнение, и подписывает полученный результат.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Входной массив данных. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Алгоритм хеширования. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Режим заполнения. Возвращает подпись [RSA](../) для входных данных. |

## RSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method

Вычисляет значение хеша указанного массива данных, используя указанный алгоритм хеширования и заполнение, и подписывает полученный результат.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Входной массив данных. |
| offset | **int32_t** | Смещение в **data**. |
| count | **int32_t** | Количество байтов, используемых в качестве входных данных. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Алгоритм хеширования. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Режим заполнения. Возвращает подпись [RSA](../) для входных данных. |

## RSA::SignData(const StreamPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method

Вычисляет значение хеша указанного двоичного потока, используя указанный алгоритм хеширования и заполнение, и подписывает полученный результат.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Бинарный поток. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Алгоритм хеширования. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Режим заполнения. Возвращает подпись [RSA](../) для входных данных. |

## См. также

* Тип [ByteArrayPtr](../../../system/bytearrayptr/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Тип [StreamPtr](../../../system/streamptr/)
* Класс [RSASignaturePadding](../../rsasignaturepadding/)
* Класс [RSA](../)
* Структура [HashAlgorithmName](../../hashalgorithmname/)
* Пространство имён [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)