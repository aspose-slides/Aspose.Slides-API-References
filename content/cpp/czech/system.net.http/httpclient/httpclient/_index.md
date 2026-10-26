---
title: HttpClient()
second_title: Aspose.Slides pro C++ referenci API
description: Vytvoří novou instanci.
type: docs
weight: 92
url: /cs/system.net.http/httpclient/httpclient/
---
## HttpClient::HttpClient() konstruktor


Vytvoří novou instanci.

```cpp
System::Net::Http::HttpClient::HttpClient()
```

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>) konstruktor


Vytvoří novou instanci.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | HTTP handler používaný pro odesílání požadavků. |

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>, bool) konstruktor


Vytvoří novou instanci.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | HTTP handler používaný pro odesílání požadavků. |
| disposeHandler | **bool** | Hodnota, která určuje, zda má být handler uvolněn, když je tato instance uvolněna. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [HttpClient](../)
* Třída [HttpMessageHandler](../../httpmessagehandler/)
* Jmenný prostor [System::Net::Http](../../)
* Knihovna [Aspose.Slides](../../../)