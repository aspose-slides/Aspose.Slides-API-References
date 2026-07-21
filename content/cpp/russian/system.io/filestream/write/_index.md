---
title: Write()
second_title: Aspose.Slides для C++ справочник API
description: Записывает указанный поддиапазон байтов из указанного массива байтов в поток.
type: docs
weight: 248
url: /ru/system.io/filestream/write/
---
## FileStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) метод

Записывает указанный поддиапазон байтов из указанного массива байтов в поток.

```cpp
void System::IO::FileStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив, содержащий байты для записи. |
| offset | **int32_t** | Нулевой индекс элемента в **buffer**, с которого начинается поддиапазон для записи. |
| count | **int32_t** | Количество элементов в поддиапазоне для записи. |

## FileStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) метод

Записывает указанный поддиапазон байтов из указанного массива байтов в поток.

```cpp
void System::IO::FileStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Представление массива, содержащее байты для записи. |
| offset | **int32_t** | Нулевой индекс элемента в **buffer**, с которого начинается поддиапазон для записи. |
| count | **int32_t** | Количество элементов в поддиапазоне для записи. |

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [FileStream](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)