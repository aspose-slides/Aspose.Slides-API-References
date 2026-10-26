---
title: Write()
second_title: Aspose.Slides для C++ API Reference
description: Если режим обёртывания бинарный, записывает в поток указанный поддиапазон байтов из заданного массива байтов, иначе преобразует указанный поддиапазон байтов из заданного массива байтов в тип char_type и затем записывает результат в поток.
type: docs
weight: 79
url: /ru/system.io/basicstdiostreamwrapper/write/
---
## BasicSTDIOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) метод

Если wrapping mode бинарный, записывает в stream указанный поддиапазон байтов из указанного массива байтов, в противном случае преобразует указанный поддиапазон байтов из указанного массива байтов в тип char_type и затем записывает результат в stream.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив, содержащий байты для записи |
| offset | **int32_t** | Нулевой (0-based) индекс элемента в **buffer**, с которого начинается поддиапазон для записи |
| count | **int32_t** | Количество элементов в поддиапазоне для записи |

## BasicSTDIOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) метод

Записывает указанный поддиапазон байтов из указанного массива байтов в stream.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Представление массива, содержащего байты для записи |
| offset | **int32_t** | Нулевой (0-based) индекс элемента в **buffer**, с которого начинается поддиапазон для записи |
| count | **int32_t** | Количество элементов в поддиапазоне для записи |

## См. также

* Тип-определение [ArrayPtr](../../../system/arrayptr/)
* Класс [BasicSTDIOStreamWrapper](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)