---
title: HashData()
second_title: Aspose.Slides для C++ справочник API
description: Вычисляет хеш-значение указанного массива данных с использованием указанного алгоритма хеширования.
type: docs
weight: 105
url: /ru/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) метод


Вычисляет хеш-значение указанного массива данных с использованием указанного алгоритма хеширования.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) для хеширования. |
| offset | **int32_t** | Смещение в **data**. |
| count | **int32_t** | Количество байтов для хеширования. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Алгоритм хеширования. |

### Возвращаемое значение

Хешированные данные.

## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) метод


Вычисляет хеш-значение указанного бинарного потока с использованием указанного алгоритма хеширования.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [StreamPtr](../../../system/streamptr/) | Бинарный поток для хеширования. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Алгоритм хеширования. |

### Возвращаемое значение

Хешированные данные.

## См. также

* Тип [ByteArrayPtr](../../../system/bytearrayptr/)
* Тип [StreamPtr](../../../system/streamptr/)
* Класс [ECDsaBotan](../)
* Структура [HashAlgorithmName](../../hashalgorithmname/)
* Пространство имён [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)