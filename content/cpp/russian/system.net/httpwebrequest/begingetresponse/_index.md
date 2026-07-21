---
title: BeginGetResponse()
second_title: Aspose.Slides для C++ справка по API
description: Инициирует асинхронный запрос ресурса.
type: docs
weight: 495
url: /ru/system.net/httpwebrequest/begingetresponse/
---
## HttpWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) метод

Инициирует асинхронный запрос ресурса.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Обратный вызов, который будет вызван после завершения операции. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Данные, предоставленные пользователем, используемые для уникальной идентификации каждой асинхронной операции. |

### Возвращаемое значение

Объект [IAsyncResult](../../../system/iasyncresult/), представляющий инициированную асинхронную операцию.

## См. также

* Определение типа [SharedPtr](../../../system/sharedptr/)
* Определение типа [AsyncCallback](../../../system/asynccallback/)
* Класс [IAsyncResult](../../../system/iasyncresult/)
* Класс [Object](../../../system/object/)
* Класс [HttpWebRequest](../)
* Пространство имён [System::Net](../../)
* Библиотека [Aspose.Slides](../../../)