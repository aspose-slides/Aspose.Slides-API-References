---
title: HttpClient()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye una nueva instancia.
type: docs
weight: 92
url: /es/system.net.http/httpclient/httpclient/
---
## HttpClient::HttpClient() constructor

Construye una nueva instancia.

```cpp
System::Net::Http::HttpClient::HttpClient()
```

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>) constructor

Construye una nueva instancia.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | El controlador HTTP utilizado para enviar solicitudes. |

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>, bool) constructor

Construye una nueva instancia.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | El controlador HTTP utilizado para enviar solicitudes. |
| disposeHandler | **bool** | El valor que indica si el controlador debe liberarse cuando esta instancia se libere. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpClient](../)
* Class [HttpMessageHandler](../../httpmessagehandler/)
* Namespace [System::Net::Http](../../)
* Library [Aspose.Slides](../../../)