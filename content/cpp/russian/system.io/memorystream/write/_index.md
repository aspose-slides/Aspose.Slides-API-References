---
title: Write()
second_title: Справочник API Aspose.Slides для C++
description: Записывает указанный поддиапазон байтов из указанного массива байт в поток.
type: docs
weight: 92
url: /ru/system.io/memorystream/write/
---
## MemoryStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) метод

Записывает указанный поддиапазон байтов из указанного массива байт в поток.

```cpp
void System::IO::MemoryStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив, содержащий байты для записи |
| offset | **int32_t** | Индекс, начинающийся с 0, элемента в **buffer**, с которого начинается поддиапазон для записи |
| count | **int32_t** | Количество элементов в поддиапазоне для записи |

## MemoryStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) метод

Записывает указанный поддиапазон байтов из указанного массива байт в поток.

```cpp
void System::IO::MemoryStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Представление массива, содержащего байты для записи |
| offset | **int32_t** | Индекс, начинающийся с 0, элемента в **buffer**, с которого начинается поддиапазон для записи |
| count | **int32_t** | Количество элементов в поддиапазоне для записи |

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [MemoryStream](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)