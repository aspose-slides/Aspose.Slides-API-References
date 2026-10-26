---
title: HttpClient()
second_title: Aspose.Slides C++ API referenciája
description: Új példányt hoz létre.
type: docs
weight: 92
url: /hu/system.net.http/httpclient/httpclient/
---
## HttpClient::HttpClient() konstruktor


Új példányt hoz létre.

```cpp
System::Net::Http::HttpClient::HttpClient()
```

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>) konstruktor


Új példányt hoz létre.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | A kérések küldéséhez használt HTTP kezelő. |

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>, bool) konstruktor


Új példányt hoz létre.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | A kérések küldéséhez használt HTTP kezelő. |
| disposeHandler | **bool** | Az érték, amely jelzi, hogy a kezelőt el kell-e bocsátani, amikor ezt a példányt elbocsátják. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [HttpClient](../)
* Osztály [HttpMessageHandler](../../httpmessagehandler/)
* Névtér [System::Net::Http](../../)
* Könyvtár [Aspose.Slides](../../../)