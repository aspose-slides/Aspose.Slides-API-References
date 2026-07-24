---
title: HttpClient()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine neue Instanz.
type: docs
weight: 92
url: /de/system.net.http/httpclient/httpclient/
---
## HttpClient::HttpClient() Konstruktor


Erstellt eine neue Instanz.

```cpp
System::Net::Http::HttpClient::HttpClient()
```

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>) Konstruktor


Erstellt eine neue Instanz.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | Der HTTP-Handler, der zum Senden von Anfragen verwendet wird. |

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>, bool) Konstruktor


Erstellt eine neue Instanz.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | Der HTTP-Handler, der zum Senden von Anfragen verwendet wird. |
| disposeHandler | **bool** | Der Wert, der angibt, ob der Handler freigegeben werden muss, wenn diese Instanz freigegeben wird. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [HttpClient](../)
* Klasse [HttpMessageHandler](../../httpmessagehandler/)
* Namensraum [System::Net::Http](../../)
* Bibliothek [Aspose.Slides](../../../)