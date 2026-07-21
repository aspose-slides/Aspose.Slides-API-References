---
title: BeginGetResponse()
second_title: Aspose.Slides для C++ API справка
description: Инициирует асинхронный запрос к ресурсу.
type: docs
weight: 274
url: /ru/system.net/webrequest/begingetresponse/
---
## WebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) метод


Инициирует асинхронный запрос к ресурсу.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state)=0
```


### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Callback, вызываемый при завершении операции. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Данные, предоставленные пользователем, используемые для уникальной идентификации каждой асинхронной операции. |

### Возвращаемое значение

Объект [IAsyncResult](../../../system/iasyncresult/), представляющий инициированную асинхронную операцию.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Класс [IAsyncResult](../../../system/iasyncresult/)
* Класс [Object](../../../system/object/)
* Класс [WebRequest](../)
* Пространство имён [System::Net](../../)
* Библиотека [Aspose.Slides](../../../)