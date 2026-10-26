---
title: Read()
second_title: Aspose.Slides для C++ Справка API
description: Если режим обёртки бинарный, считывает указанное количество байтов из потока, иначе считывает указанное количество символов и преобразует их в тип uint8_t. Записывает результат чтения в указанный массив байтов.
type: docs
weight: 66
url: /ru/system.io/basicstdiostreamwrapper/read/
---
## BasicSTDIOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) метод

Если режим обёртки бинарный, читается указанное количество байтов из потока, в противном случае читается указанное количество символов и преобразуется в тип **uint8_t**. Результат чтения записывается в указанный массив байтов.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив байтов, в который записываются прочитанные байты |
| offset | **int32_t** | Позиция в **buffer**, начинающаяся с 0, с которой начать запись |
| count | **int32_t** | Количество байтов для чтения |

### Возвращаемое значение

Количество прочитанных байтов или символов

## BasicSTDIOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) метод

Читает указанное количество байтов из потока и записывает их в указанный массив байтов.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Представление массива байтов, в которое записываются прочитанные байты |
| offset | **int32_t** | Позиция в **buffer**, начинающаяся с 0, с которой начать запись |
| count | **int32_t** | Количество байтов для чтения |

### Возвращаемое значение

Количество прочитанных байтов

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDIOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)