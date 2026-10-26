---
title: EndGetResponse()
second_title: Справочник API Aspose.Slides для C++
description: Ожидает, пока указанный асинхронный запрос ресурса не завершится.
type: docs
weight: 508
url: /ru/system.net/httpwebrequest/endgetresponse/
---
## HttpWebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) метод

Ожидает, пока указанный асинхронный запрос ресурса не завершится.

```cpp
System::SharedPtr<WebResponse> System::Net::HttpWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Объект [IAsyncResult](../../../system/iasyncresult/), представляющий асинхронный запрос ресурса. |

### Возвращаемое значение

Веб-ответ.

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [WebResponse](../../webresponse/)
* Класс [IAsyncResult](../../../system/iasyncresult/)
* Класс [HttpWebRequest](../)
* Пространство имён [System::Net](../../)
* Библиотека [Aspose.Slides](../../../)