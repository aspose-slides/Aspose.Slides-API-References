---
title: ComputeHash()
second_title: Aspose.Slides для C++: справочник API
description: Хеширует буфер.
type: docs
weight: 14
url: /ru/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) метод


Хеширует буфер.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```


### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Исходный буфер. |

### Возвращаемое значение

Вычисленное значение хеша.

## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) метод


Хеширует часть буфера.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```


### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Исходный буфер. |
| offset | int | Смещение в исходном буфере. |
| count | int | Количество байтов, используемых из исходного буфера. |

### Возвращаемое значение

Вычисленное значение хеша.

## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) метод


Читает поток до конца и вычисляет хеш прочитанных данных.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```


### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> const\& | Поток, из которого читаются данные. |

### Возвращаемое значение

Вычисленное значение хеша для всех данных потока.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [HashAlgorithm](../)
* Класс [Stream](../../../system.io/stream/)
* Пространство имён [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)