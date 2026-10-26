---
title: Details_WebException()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova istanza.
type: docs
weight: 40
url: /it/system.net/details_webexception/details_webexception/
---
## Details_WebException::Details_WebException() costruttore

Crea una nuova istanza.

```cpp
System::Net::Details_WebException::Details_WebException()
```

## Details_WebException::Details_WebException(String) costruttore

Crea una nuova istanza.

```cpp
System::Net::Details_WebException::Details_WebException(String message)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| message | [String](../../../system/string/) | La descrizione dell'errore. |

## Details_WebException::Details_WebException(String, Exception) costruttore

Crea una nuova istanza.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| message | [String](../../../system/string/) | Il messaggio dell'eccezione. |
| innerException | [Exception](../../../system/exception/) | L'eccezione interna. |

## Details_WebException::Details_WebException(String, WebExceptionStatus) costruttore

Crea una nuova istanza.

```cpp
System::Net::Details_WebException::Details_WebException(String message, WebExceptionStatus status)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| message | [String](../../../system/string/) | Il messaggio dell'eccezione. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | Il codice di stato. |

## Details_WebException::Details_WebException(String, Exception, WebExceptionStatus, System::SharedPtr\<WebResponse\>) costruttore

Crea una nuova istanza.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException, WebExceptionStatus status, System::SharedPtr<WebResponse> response)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| message | [String](../../../system/string/) | Il messaggio dell'eccezione. |
| innerException | [Exception](../../../system/exception/) | L'eccezione interna. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | Il codice di stato. |
| response | [System::SharedPtr](../../../system/sharedptr/)\<[WebResponse](../../webresponse/)\> | La risposta web associata all'eccezione corrente. |

## Vedi anche

* Enum [WebExceptionStatus](../../webexceptionstatus/)
* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Details_WebException](../)
* Classe [String](../../../system/string/)
* Classe [WebResponse](../../webresponse/)
* Spazio dei nomi [System::Net](../../)
* Library [Aspose.Slides](../../../)