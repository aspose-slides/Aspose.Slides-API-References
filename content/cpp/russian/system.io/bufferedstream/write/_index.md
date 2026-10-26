---
title: Write()
second_title: Aspose.Slides для C++ справка по API
description: Записывает указанный подпоследовательный диапазон байтов из указанного массива байтов в базовый поток.
type: docs
weight: 66
url: /ru/system.io/bufferedstream/write/
---
## BufferedStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) метод


Записывает указанный подпоследовательный диапазон байтов из указанного массива байтов в базовый поток.

```cpp
virtual void System::IO::BufferedStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив, содержащий байты для записи |
| offset | **int32_t** | Нулевой индекс элемента в **buffer**, с которого начинается записываемый подпоследовательный диапазон |
| count | **int32_t** | Количество элементов в записываемом подпоследовательном диапазоне |

## BufferedStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) метод


Записывает указанный подпоследовательный диапазон байтов из указанного массива байтов в базовый поток.

```cpp
virtual void System::IO::BufferedStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Массив, содержащий байты для записи |
| offset | **int32_t** | Нулевой индекс элемента в **buffer**, с которого начинается записываемый подпоследовательный диапазон |
| count | **int32_t** | Количество элементов в записываемом подпоследовательном диапазоне |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [BufferedStream](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)