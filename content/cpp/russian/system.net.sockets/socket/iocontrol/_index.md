---
title: IOControl()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает низкоуровневые режимы работы для сокета.
type: docs
weight: 703
url: /ru/system.net.sockets/socket/iocontrol/
---
## Socket::IOControl(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) метод

Устанавливает низкоуровневые режимы работы для сокета.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(int32_t ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ioControlCode | **int32_t** | The control code of the operation to perform. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The byte array that contains the input data. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The byte array that contains the output data. |

### Возвращаемое значение

Количество байтов в параметре **optionOutValue**.

## Socket::IOControl(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) метод

Устанавливает низкоуровневые режимы работы для сокета.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(IOControlCode ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ioControlCode | [IOControlCode](../../iocontrolcode/) | The control code of the operation to perform. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The byte array that contains the input data. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The byte array that contains the output data. |

### Возвращаемое значение

Количество байтов в параметре **optionOutValue**.

## См. также

* Перечисление [IOControlCode](../../iocontrolcode/)
* Типовое определение [ArrayPtr](../../../system/arrayptr/)
* Класс [Socket](../)
* Пространство имён [System::Net::Sockets](../../)
* Библиотека [Aspose.Slides](../../../)