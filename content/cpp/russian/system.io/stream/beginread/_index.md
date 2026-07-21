---
title: BeginRead()
second_title: Aspose.Slides для C++ справочник API
description: Инициирует асинхронную операцию чтения.
type: docs
weight: 157
url: /ru/system.io/stream/beginread/
---
## Stream::BeginRead(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) метод


Инициирует асинхронную операцию чтения.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Буфер для чтения |
| offset | int | Смещение, начинающееся с 0 в **buffer**, указывающее позицию, с которой начинать запись прочитанных данных |
| count | int | Количество байтов для чтения |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | Обратный вызов, который будет вызван по завершении операции |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Пользовательские данные, используемые для уникальной идентификации каждой асинхронной операции чтения |

### Возвращаемое значение

Объект [IAsyncResult](../../../system/iasyncresult/), представляющий инициированную асинхронную операцию чтения

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Класс [IAsyncResult](../../../system/iasyncresult/)
* Класс [Object](../../../system/object/)
* Класс [Stream](../)
* Пространство имён [System::IO](../../)
* Library [Aspose.Slides](../../../)