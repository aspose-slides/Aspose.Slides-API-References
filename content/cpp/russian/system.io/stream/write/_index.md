---
title: Write()
second_title: Справочник API Aspose.Slides для C++
description: Записывает указанный диапазон байтов из указанного массива байтов в поток.
type: docs
weight: 53
url: /ru/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) метод

Записывает указанный диапазон байтов из указанного массива байтов в поток.

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив, содержащий байты для записи |
| offset | **int32_t** | Индекс, начинающийся с 0, элемента в **buffer**, с которого начинается записываемый диапазон |
| count | **int32_t** | Количество элементов в записываемом диапазоне |

## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) метод

Записывает указанный диапазон байтов из указанного массива байтов в поток.

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Представление массива, содержащего байты для записи |
| offset | **int32_t** | Индекс, начинающийся с 0, элемента в **buffer**, с которого начинается записываемый диапазон |
| count | **int32_t** | Количество элементов в записываемом диапазоне |

## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) метод

Записывает указанный диапазон байтов из указанного массива байтов в поток.

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| N | Размер стекового массива |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | Стековый массив, содержащий байты для записи |
| offset | **int32_t** | Индекс, начинающийся с 0, элемента в **buffer**, с которого начинается записываемый диапазон |
| count | **int32_t** | Количество элементов в записываемом диапазоне |

## Stream::Write(const System::ReadOnlySpan\<uint8_t\>\&) метод

Записывает указанный диапазон байтов из указанного спана байтов в поток.

```cpp
virtual void System::IO::Stream::Write(const System::ReadOnlySpan<uint8_t> &buffer)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [System::ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | Спан байтов, из которого читаются записываемые байты |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [Stream](../)
* Класс [ReadOnlySpan](../../../system/readonlyspan/)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)