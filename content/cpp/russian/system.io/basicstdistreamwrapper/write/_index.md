---
title: Write()
second_title: Справочник API Aspose.Slides для C++
description: Если режим обёртывания бинарный, записывает в поток указанный поддиапазон байтов из указанного массива байтов, иначе преобразует указанный поддиапазон байтов из указанного массива байтов к типу char_type и затем записывает результат в поток. Не поддерживается!
type: docs
weight: 79
url: /ru/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) метод

Если режим обёртывания бинарный, записывает в поток указанный поддиапазон байтов из указанного массива байтов, иначе преобразует указанный поддиапазон байтов из указанного массива байтов к типу `char_type` и затем записывает результат в поток. Не поддерживается!

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив, содержащий байты для записи. |
| offset | **int32_t** | Нулевой индекс элемента в **buffer**, с которого начинается поддиапазон для записи. |
| count | **int32_t** | Количество элементов в поддиапазоне для записи. |

## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) метод

Записывает указанный поддиапазон байтов из указанного массива байтов в поток.

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Представление массива, содержащего байты для записи |
| offset | **int32_t** | Нулевой индекс элемента в **buffer**, с которого начинается поддиапазон для записи |
| count | **int32_t** | Количество элементов в поддиапазоне для записи |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [BasicSTDIStreamWrapper](../)
* Простейство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)