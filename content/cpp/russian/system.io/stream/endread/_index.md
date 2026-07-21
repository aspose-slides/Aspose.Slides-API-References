---
title: EndRead()
second_title: Aspose.Slides для C++ Справочник API
description: Ожидает завершения указанной асинхронной операции чтения.
type: docs
weight: 183
url: /ru/system.io/stream/endread/
---
## Stream::EndRead(System::SharedPtr\<System::IAsyncResult\>) метод

Ожидает завершения указанной асинхронной операции чтения.

```cpp
virtual int System::IO::Stream::EndRead(System::SharedPtr<System::IAsyncResult> asyncResult)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[System::IAsyncResult](../../../system/iasyncresult/)\> | Объект [IAsyncResult](../../../system/iasyncresult/), представляющий асинхронную операцию чтения |

### Возвращаемое значение

Количество байтов, прочитанных во время операции чтения, представленной **asyncResult**

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IAsyncResult](../../../system/iasyncresult/)
* Класс [Stream](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)