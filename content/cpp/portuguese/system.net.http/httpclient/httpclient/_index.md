---
title: HttpClient()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância.
type: docs
weight: 92
url: /pt/system.net.http/httpclient/httpclient/
---
## HttpClient::HttpClient() construtor


Constrói uma nova instância.

```cpp
System::Net::Http::HttpClient::HttpClient()
```

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>) construtor


Constrói uma nova instância.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | O manipulador HTTP usado para enviar solicitações. |

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>, bool) construtor


Constrói uma nova instância.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | O manipulador HTTP usado para enviar solicitações. |
| disposeHandler | **bool** | O valor que indica se o manipulador deve ser descartado quando esta instância for descartada. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [HttpClient](../)
* Classe [HttpMessageHandler](../../httpmessagehandler/)
* Espaço de nomes [System::Net::Http](../../)
* Biblioteca [Aspose.Slides](../../../)