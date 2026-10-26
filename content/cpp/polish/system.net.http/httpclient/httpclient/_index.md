---
title: HttpClient()
second_title: Aspose.Slides dla C++ API Reference
description: Tworzy nową instancję.
type: docs
weight: 92
url: /pl/system.net.http/httpclient/httpclient/
---
## HttpClient::HttpClient() konstruktor

Tworzy nową instancję.

```cpp
System::Net::Http::HttpClient::HttpClient()
```

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>) konstruktor

Tworzy nową instancję.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | Obsługa HTTP używana do wysyłania żądań. |

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>, bool) konstruktor

Tworzy nową instancję.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | Obsługa HTTP używana do wysyłania żądań. |
| disposeHandler | **bool** | Wartość wskazująca, czy obsługa musi zostać zwolniona, gdy ta instancja zostanie zwolniona. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpClient](../)
* Class [HttpMessageHandler](../../httpmessagehandler/)
* Namespace [System::Net::Http](../../)
* Library [Aspose.Slides](../../../)