---
title: SignData()
second_title: Справочная документация API Aspose.Slides для C++
description: Вычисляет хеш-значение указанного массива данных с использованием указанного алгоритма хеширования и подписывает результат.
type: docs
weight: 79
url: /ru/system.security.cryptography/ecdsa/signdata/
---
## ECDsa::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) метод


Вычисляет хеш-значение указанного массива данных с использованием указанного алгоритма хеширования и подписывает результат.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Входной массив данных. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Алгоритм хеширования. Возвращает подпись ECDSA для входных данных. |

## ECDsa::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) метод


Вычисляет хеш-значение указанного массива данных с использованием указанного алгоритма хеширования и подписывает результат.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Входной массив данных. |
| offset | **int32_t** | Смещение в **data**. |
| count | **int32_t** | Количество байтов, используемых в качестве входных данных. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Алгоритм хеширования. Возвращает подпись ECDSA для входных данных. |

## ECDsa::SignData(const StreamPtr\&, const HashAlgorithmName\&) метод


Вычисляет хеш-значение указанного двоичного потока с использованием указанного алгоритма хеширования и подписывает результат.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Бинарный поток. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Алгоритм хеширования. Возвращает подпись ECDSA для входных данных. |

## См. также

* Тип-определение [ByteArrayPtr](../../../system/bytearrayptr/)
* Тип-определение [StreamPtr](../../../system/streamptr/)
* Класс [ECDsa](../)
* Структура [HashAlgorithmName](../../hashalgorithmname/)
* Пространство имён [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)