---
title: Write()
second_title: Справочник API Aspose.Slides для C++
description: Записывает указанный диапазон байтов из указанного массива байтов в поток.
type: docs
weight: 209
url: /ru/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) метод

Записывает указанный диапазон байтов из указанного массива байтов в поток.

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив, содержащий байты для записи. |
| offset | **int32_t** | Смещение в байтах в указанном массиве. |
| size | **int32_t** | Количество элементов в диапазоне для записи. |

## NetworkStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) метод

Записывает указанный диапазон байтов из указанного массива байтов в поток.

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Представление массива, содержащего байты для записи |
| offset | **int32_t** | Нулевой индекс элемента в **buffer**, с которого начинается диапазон для записи |
| size | **int32_t** | Количество элементов в диапазоне для записи |

## См. также

* Типовое определение [ArrayPtr](../../../system/arrayptr/)
* Класс [NetworkStream](../)
* Пространство имён [System::Net::Sockets](../../)
* Библиотека [Aspose.Slides](../../../)