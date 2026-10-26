---
title: Details_WebException()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância.
type: docs
weight: 40
url: /pt/system.net/details_webexception/details_webexception/
---
## Details_WebException::Details_WebException() construtor

Constrói uma nova instância.

```cpp
System::Net::Details_WebException::Details_WebException()
```

## Details_WebException::Details_WebException(String) construtor

Constrói uma nova instância.

```cpp
System::Net::Details_WebException::Details_WebException(String message)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| message | [String](../../../system/string/) | A descrição do erro. |

## Details_WebException::Details_WebException(String, Exception) construtor

Constrói uma nova instância.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| message | [String](../../../system/string/) | A mensagem da exceção. |
| innerException | [Exception](../../../system/exception/) | A exceção interna. |

## Details_WebException::Details_WebException(String, WebExceptionStatus) construtor

Constrói uma nova instância.

```cpp
System::Net::Details_WebException::Details_WebException(String message, WebExceptionStatus status)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| message | [String](../../../system/string/) | A mensagem da exceção. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | O código de status. |

## Details_WebException::Details_WebException(String, Exception, WebExceptionStatus, System::SharedPtr\<WebResponse\>) construtor

Constrói uma nova instância.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException, WebExceptionStatus status, System::SharedPtr<WebResponse> response)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| message | [String](../../../system/string/) | A mensagem da exceção. |
| innerException | [Exception](../../../system/exception/) | A exceção interna. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | O código de status. |
| response | [System::SharedPtr](../../../system/sharedptr/)\<[WebResponse](../../webresponse/)\> | A resposta web com a qual a exceção atual está associada. |

## See Also

* Enum [WebExceptionStatus](../../webexceptionstatus/)
* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Details_WebException](../)
* Class [String](../../../system/string/)
* Class [WebResponse](../../webresponse/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)