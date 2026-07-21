---
title: Write()
second_title: Aspose.Slides для C++ справочник API
description: Записывает указанный массив байтов в поток.
type: docs
weight: 404
url: /ru/system.net.security/sslstream/write/
---
## SslStream::Write(const ArrayPtr\<uint8_t\>\&) метод


Записывает указанный массив байтов в поток.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив байтов для записи. |

## SslStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) метод


Записывает указанный поддиапазон байтов из указанного массива байтов в поток.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив, содержащий байты для записи |
| offset | **int32_t** | Нулевой индекс элемента в **buffer**, с которого начинается поддиапазон для записи |
| count | **int32_t** | Количество элементов в поддиапазоне для записи |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&) метод


Записывает указанный массив байтов в поток.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Массив байтов для записи. |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) метод


Записывает указанный поддиапазон байтов из указанного массива байтов в поток.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Массив, содержащий байты для записи |
| offset | **int32_t** | Нулевой индекс элемента в **buffer**, с которого начинается поддиапазон для записи |
| count | **int32_t** | Количество элементов в поддиапазоне для записи |

## Смотрите также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [SslStream](../)
* Пространство имён [System::Net::Security](../../)
* Библиотека [Aspose.Slides](../../../)