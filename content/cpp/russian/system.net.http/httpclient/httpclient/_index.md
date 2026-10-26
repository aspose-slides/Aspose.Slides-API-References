---
title: HttpClient()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт новый экземпляр.
type: docs
weight: 92
url: /ru/system.net.http/httpclient/httpclient/
---
## HttpClient::HttpClient() конструктор

Создает новый экземпляр.

```cpp
System::Net::Http::HttpClient::HttpClient()
```

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>) конструктор

Создает новый экземпляр.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | HTTP-обработчик, используемый для отправки запросов. |

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>, bool) конструктор

Создает новый экземпляр.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | HTTP-обработчик, используемый для отправки запросов. |
| disposeHandler | **bool** | Значение, указывающее, должен ли обработчик быть удалён при удалении этого экземпляра. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [HttpClient](../)
* Класс [HttpMessageHandler](../../httpmessagehandler/)
* Пространство имён [System::Net::Http](../../)
* Библиотека [Aspose.Slides](../../../)