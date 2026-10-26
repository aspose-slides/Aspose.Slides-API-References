---
title: EndGetRequestStream()
second_title: Справочник API Aspose.Slides для C++
description: Ожидает завершения указанной асинхронной операции получения потока.
type: docs
weight: 157
url: /ru/system.net/filewebrequest/endgetrequeststream/
---
## FileWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) метод

Ожидает завершения указанной асинхронной операции получения потока.

```cpp
System::SharedPtr<IO::Stream> System::Net::FileWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Объект [IAsyncResult](../../../system/iasyncresult/), представляющий асинхронную операцию получения потока. |

### Возвращаемое значение

Поток для записи данных в ресурс.

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Stream](../../../system.io/stream/)
* Класс [IAsyncResult](../../../system/iasyncresult/)
* Класс [FileWebRequest](../)
* Пространство имён [System::Net](../../)
* Библиотека [Aspose.Slides](../../../)