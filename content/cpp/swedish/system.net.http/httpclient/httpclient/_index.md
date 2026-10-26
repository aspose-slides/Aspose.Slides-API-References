---
title: HttpClient()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans.
type: docs
weight: 92
url: /sv/system.net.http/httpclient/httpclient/
---
## HttpClient::HttpClient() konstruktor

Skapar en ny instans.

```cpp
System::Net::Http::HttpClient::HttpClient()
```

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>) konstruktor

Skapar en ny instans.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | HTTP-hanteraren som används för att skicka förfrågningar. |

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>, bool) konstruktor

Skapar en ny instans.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | HTTP-hanteraren som används för att skicka förfrågningar. |
| disposeHandler | **bool** | Värdet som anger om hanteraren ska frigöras när denna instans frigörs. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [HttpClient](../)
* Klass [HttpMessageHandler](../../httpmessagehandler/)
* Namnrymd [System::Net::Http](../../)
* Bibliotek [Aspose.Slides](../../../)