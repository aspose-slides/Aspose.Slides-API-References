---
title: HttpRequestMessage()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit une nouvelle instance.
type: docs
weight: 131
url: /fr/system.net.http/httprequestmessage/httprequestmessage/
---
## HttpRequestMessage::HttpRequestMessage() constructeur

Construit une nouvelle instance.

```cpp
System::Net::Http::HttpRequestMessage::HttpRequestMessage()
```

## HttpRequestMessage::HttpRequestMessage(System::SharedPtr\<HttpMethod\>, System::SharedPtr\<Uri\>) constructeur

Construit une nouvelle instance.

```cpp
System::Net::Http::HttpRequestMessage::HttpRequestMessage(System::SharedPtr<HttpMethod> method, System::SharedPtr<Uri> requestUri)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| method | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMethod](../../httpmethod/)\> | La méthode HTTP. |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI de la ressource demandée. |

## HttpRequestMessage::HttpRequestMessage(System::SharedPtr\<HttpMethod\>, String) constructeur

Construit une nouvelle instance.

```cpp
System::Net::Http::HttpRequestMessage::HttpRequestMessage(System::SharedPtr<HttpMethod> method, String requestUri)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| method | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMethod](../../httpmethod/)\> | La méthode HTTP. |
| requestUri | [String](../../../system/string/) | L'URI de la ressource demandée. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [HttpRequestMessage](../)
* Classe [HttpMethod](../../httpmethod/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Espace de noms [System::Net::Http](../../)
* Bibliothèque [Aspose.Slides](../../../)