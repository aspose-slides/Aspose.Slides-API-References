---
title: HttpMessageInvoker()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт новый экземпляр.
type: docs
weight: 1
url: /ru/system.net.http/httpmessageinvoker/httpmessageinvoker/
---
## HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr\<HttpMessageHandler\>) конструктор

Создаёт новый экземпляр.

```cpp
System::Net::Http::HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr<HttpMessageHandler> handler)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | HTTP-обработчик, используемый для отправки запросов. |

## HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr\<HttpMessageHandler\>, bool) конструктор

Создаёт новый экземпляр.

```cpp
System::Net::Http::HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | HTTP-обработчик, используемый для отправки запросов. |
| disposeHandler | **bool** | Значение, указывающее, должен ли обработчик быть освобождён, когда этот экземпляр освобождается. |

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [HttpMessageHandler](../../httpmessagehandler/)
* Класс [HttpMessageInvoker](../)
* Пространство имён [System::Net::Http](../../)
* Библиотека [Aspose.Slides](../../../)