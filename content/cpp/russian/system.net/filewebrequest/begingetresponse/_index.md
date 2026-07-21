---
title: BeginGetResponse()
second_title: Справочник API Aspose.Slides для C++
description: Инициирует асинхронный запрос ресурса.
type: docs
weight: 170
url: /ru/system.net/filewebrequest/begingetresponse/
---
## FileWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) метод

Инициирует асинхронный запрос ресурса.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Обратный вызов, который будет вызван после завершения операции. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Пользовательские данные, используемые для уникальной идентификации каждой асинхронной операции. |

### Возвращаемое значение

Объект [IAsyncResult](../../../system/iasyncresult/), представляющий инициированную асинхронную операцию.

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Класс [IAsyncResult](../../../system/iasyncresult/)
* Класс [Object](../../../system/object/)
* Класс [FileWebRequest](../)
* Пространство имён [System::Net](../../)
* Library [Aspose.Slides](../../../)