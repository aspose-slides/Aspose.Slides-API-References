---
title: Read()
second_title: Aspose.Slides для C++ справочник API
description: Если режим обёртывания бинарный, читает указанное количество байтов из потока, иначе читает указанное количество символов и преобразует их в тип uint8_t. Записывает результат чтения в указанный массив байтов.
type: docs
weight: 66
url: /ru/system.io/basicstdistreamwrapper/read/
---
## BasicSTDIStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) метод

Если режим обёртывания бинарный, читает указанное количество байтов из потока, иначе читает указанное количество символов и преобразует их к типу **uint8_t**. Записывает результат чтения в указанный массив байтов.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив байтов, в который записываются прочитанные байты |
| offset | **int32_t** | 0-базовая позиция в **buffer**, с которой начинается запись |
| count | **int32_t** | Количество байтов для чтения |

### Возвращаемое значение

Количество прочитанных байтов или символов

## BasicSTDIStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) метод

Читает указанное количество байтов из потока и записывает их в указанный массив байтов.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Представление массива байтов, в которое записываются прочитанные байты |
| offset | **int32_t** | 0-базовая позиция в **buffer**, с которой начинается запись |
| count | **int32_t** | Количество байтов для чтения |

### Возвращаемое значение

Количество прочитанных байтов

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [BasicSTDIStreamWrapper](../)
* Пространство имён [System::IO](../../)
* Library [Aspose.Slides](../../../)