---
title: BeginGetRequestStream()
second_title: Aspose.Slides для C++ справка API
description: Инициирует асинхронную операцию получения потока для записи данных в ресурс.
type: docs
weight: 300
url: /ru/system.net/webrequest/begingetrequeststream/
---
## WebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) метод

Инициирует асинхронную операцию получения потока для записи данных в ресурс.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Обратный вызов, который будет вызван после завершения операции. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Пользовательские данные, используемые для уникальной идентификации каждой асинхронной операции. |

### Возвращаемое значение

Объект [IAsyncResult](../../../system/iasyncresult/), представляющий инициированную асинхронную операцию.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Класс [IAsyncResult](../../../system/iasyncresult/)
* Класс [Object](../../../system/object/)
* Класс [WebRequest](../)
* Пространство имён [System::Net](../../)
* Library [Aspose.Slides](../../../)