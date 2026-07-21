---
title: EndGetResponse()
second_title: Справочник API Aspose.Slides для C++
description: Ожидает завершения указанного асинхронного запроса ресурса.
type: docs
weight: 287
url: /ru/system.net/webrequest/endgetresponse/
---
## WebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) метод

Ожидает завершения указанного асинхронного запроса ресурса.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::WebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Объект [IAsyncResult](../../../system/iasyncresult/), представляющий асинхронный запрос ресурса. |

### Возвращаемое значение

Веб-ответ.

## Смотрите также

* typedef [SharedPtr](../../../system/sharedptr/)
* Класс [WebResponse](../../webresponse/)
* Класс [IAsyncResult](../../../system/iasyncresult/)
* Класс [WebRequest](../)
* Пространство имён [System::Net](../../)
* Библиотека [Aspose.Slides](../../../)