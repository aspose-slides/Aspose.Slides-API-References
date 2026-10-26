---
title: Write()
second_title: Aspose.Slides для C++ справочник API
description: Если режим обёртки бинарный, записывает в поток указанный поддиапазон байтов из указанного массива байтов, иначе преобразует указанный поддиапазон байтов из указанного массива байтов в тип char_type и затем записывает результат в поток.
type: docs
weight: 79
url: /ru/system.io/basicstdostreamwrapper/write/
---
## BasicSTDOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) метод

Если режим обёртки бинарный, записывает в поток указанный поддиапазон байтов из указанного массива байтов, иначе преобразует указанный поддиапазон байтов из указанного массива байтов в тип `char_type` и затем записывает результат в поток.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив, содержащий байты для записи |
| offset | **int32_t** | Нулевой индекс элемента в **buffer**, с которого начинается поддиапазон для записи |
| count | **int32_t** | Количество элементов в поддиапазоне для записи |

## BasicSTDOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) метод

Записывает указанный поддиапазон байтов из указанного массива байтов в поток.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Представление массива, содержащее байты для записи |
| offset | **int32_t** | Нулевой индекс элемента в **buffer**, с которого начинается поддиапазон для записи |
| count | **int32_t** | Количество элементов в поддиапазоне для записи |

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [BasicSTDOStreamWrapper](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)