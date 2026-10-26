---
title: SignData()
second_title: Справочник API Aspose.Slides для C++
description: Вычисляет подпись указанного входного значения.
type: docs
weight: 183
url: /ru/system.security.cryptography/dsacryptoserviceprovider/signdata/
---
## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&) method

Вычисляет подпись указанного входного значения.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) для чтения входных данных. |

### Возвращаемое значение

[DSA](../../dsa/) подпись для указанных данных.

## DSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&) method

Вычисляет подпись указанного входного значения.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Поток для чтения подписываемых данных. |

### Возвращаемое значение

[DSA](../../dsa/) подпись для указанных данных.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t) method

Вычисляет подпись указанного входного значения.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) для чтения входных данных. |
| offset | **int32_t** | Начальный индекс среза входного буфера. |
| count | **int32_t** | Размер среза входного буфера. |

### Возвращаемое значение

[DSA](../../dsa/) подпись для указанных данных.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) method

Вычисляет хеш-значение указанного массива данных, используя указанный алгоритм хеширования, и подписывает результат.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Массив входных данных. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Алгоритм хеширования. возвращает [DSA](../../dsa/) подпись для входных данных. |

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) method

Вычисляет хеш-значение указанного массива данных, используя указанный алгоритм хеширования, и подписывает результат.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Массив входных данных. |
| offset | **int32_t** | Смещение в **data**. |
| count | **int32_t** | Количество байтов, используемых в качестве входных данных. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Алгоритм хеширования. возвращает [DSA](../../dsa/) подпись для входных данных. |

## DSACryptoServiceProvider::SignData(const StreamPtr\&, const HashAlgorithmName\&) method

Вычисляет хеш-значение указанного двоичного потока, используя указанный алгоритм хеширования, и подписывает результат.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Двоичный поток. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Алгоритм хеширования. возвращает [DSA](../../dsa/) подпись для входных данных. |

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Класс [DSACryptoServiceProvider](../)
* Класс [Stream](../../../system.io/stream/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Пространство имён [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)