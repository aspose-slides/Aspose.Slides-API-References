---
title: EndGetRequestStream()
second_title: Справочник API Aspose.Slides для C++
description: Ожидает завершения указанной асинхронной операции получения потока.
type: docs
weight: 482
url: /ru/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) метод

Ожидает завершения указанной асинхронной операции получения потока.

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) объект, представляющий асинхронную операцию получения потока. |

### Возвращаемое значение

Поток для записи данных в ресурс.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Stream](../../../system.io/stream/)
* Класс [IAsyncResult](../../../system/iasyncresult/)
* Класс [HttpWebRequest](../)
* Пространство имён [System::Net](../../)
* Library [Aspose.Slides](../../../)