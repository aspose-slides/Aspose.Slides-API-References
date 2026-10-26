---
title: EndGetResponse()
second_title: Справочник API Aspose.Slides для C++
description: Ожидает, пока указанный асинхронный запрос ресурса не завершится.
type: docs
weight: 183
url: /ru/system.net/filewebrequest/endgetresponse/
---
## FileWebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) метод

Ожидает, пока завершится указанный асинхронный запрос ресурса.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::FileWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) объект, представляющий асинхронный запрос ресурса. |

### Возвращаемое значение

Веб-ответ.

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [WebResponse](../../webresponse/)
* Класс [IAsyncResult](../../../system/iasyncresult/)
* Класс [FileWebRequest](../)
* Пространство имён [System::Net](../../)
* Library [Aspose.Slides](../../../)