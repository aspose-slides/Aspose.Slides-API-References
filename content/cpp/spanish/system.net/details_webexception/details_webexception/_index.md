---
title: Details_WebException()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye una nueva instancia.
type: docs
weight: 40
url: /es/system.net/details_webexception/details_webexception/
---
## Details_WebException::Details_WebException() constructor

Construye una nueva instancia.

```cpp
System::Net::Details_WebException::Details_WebException()
```

## Details_WebException::Details_WebException(String) constructor

Construye una nueva instancia.

```cpp
System::Net::Details_WebException::Details_WebException(String message)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| message | [String](../../../system/string/) | La descripción del error. |

## Details_WebException::Details_WebException(String, Exception) constructor

Construye una nueva instancia.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| message | [String](../../../system/string/) | El mensaje de la excepción. |
| innerException | [Exception](../../../system/exception/) | La excepción interna. |

## Details_WebException::Details_WebException(String, WebExceptionStatus) constructor

Construye una nueva instancia.

```cpp
System::Net::Details_WebException::Details_WebException(String message, WebExceptionStatus status)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| message | [String](../../../system/string/) | El mensaje de la excepción. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | El código de estado. |

## Details_WebException::Details_WebException(String, Exception, WebExceptionStatus, System::SharedPtr\<WebResponse\>) constructor

Construye una nueva instancia.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException, WebExceptionStatus status, System::SharedPtr<WebResponse> response)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| message | [String](../../../system/string/) | El mensaje de la excepción. |
| innerException | [Exception](../../../system/exception/) | La excepción interna. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | El código de estado. |
| response | [System::SharedPtr](../../../system/sharedptr/)\<[WebResponse](../../webresponse/)\> | La respuesta web con la que está asociada la excepción actual. |

## Ver también

* Enum [WebExceptionStatus](../../webexceptionstatus/)
* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Details_WebException](../)
* Class [String](../../../system/string/)
* Class [WebResponse](../../webresponse/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)