---
title: Details_WebException()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une nouvelle instance.
type: docs
weight: 40
url: /fr/system.net/details_webexception/details_webexception/
---
## Details_WebException::Details_WebException() constructeur

Construit une nouvelle instance.

```cpp
System::Net::Details_WebException::Details_WebException()
```

## Details_WebException::Details_WebException(String) constructeur

Construit une nouvelle instance.

```cpp
System::Net::Details_WebException::Details_WebException(String message)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | La description de l'erreur. |

## Details_WebException::Details_WebException(String, Exception) constructeur

Construit une nouvelle instance.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | Le message d'exception. |
| innerException | [Exception](../../../system/exception/) | L'exception interne. |

## Details_WebException::Details_WebException(String, WebExceptionStatus) constructeur

Construit une nouvelle instance.

```cpp
System::Net::Details_WebException::Details_WebException(String message, WebExceptionStatus status)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | Le message d'exception. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | Le code d'état. |

## Details_WebException::Details_WebException(String, Exception, WebExceptionStatus, System::SharedPtr\<WebResponse\>) constructeur

Construit une nouvelle instance.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException, WebExceptionStatus status, System::SharedPtr<WebResponse> response)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | Le message d'exception. |
| innerException | [Exception](../../../system/exception/) | L'exception interne. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | Le code d'état. |
| response | [System::SharedPtr](../../../system/sharedptr/)\<[WebResponse](../../webresponse/)\> | La réponse Web avec laquelle l'exception actuelle est associée. |

## Voir aussi

* Enumération [WebExceptionStatus](../../webexceptionstatus/)
* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Details_WebException](../)
* Classe [String](../../../system/string/)
* Classe [WebResponse](../../webresponse/)
* Espace de noms [System::Net](../../)
* Bibliothèque [Aspose.Slides](../../../)