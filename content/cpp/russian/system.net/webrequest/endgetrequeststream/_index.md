---
title: EndGetRequestStream()
second_title: Aspose.Slides для C++ справочник API
description: Ожидает завершения указанной асинхронной операции получения потока.
type: docs
weight: 313
url: /ru/system.net/webrequest/endgetrequeststream/
---
## WebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) метод


Ожидает завершения указанной асинхронной операции получения потока.

```cpp
virtual System::SharedPtr<IO::Stream> System::Net::WebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Объект [IAsyncResult](../../../system/iasyncresult/), представляющий асинхронную операцию получения потока. |

### Возвращаемое значение

Поток для записи данных в ресурс.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)